---
description: Расскажем, как установить ADB на ПК для его использования.
---

# ADB через ПК

### Установка ADB на ПК

{% tabs %}
{% tab title="Текст" %}
1. Установите [архив ADB](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)
2. Установите [драйвера](../repo/drivers-pc.md)
   * [Как проверить работоспособность драйверов?](drivers-on-pc.md)
3. Распакуйте ранее скачанный архив ADB в корень диска `C:\`, а после переименуйте ее в `adb`.  &#x20;
{% endtab %}
{% endtabs %}



### Опции на смартфоне

{% tabs %}
{% tab title="Текст" %}
1. Перейдите в: «Настройки» -> «О телефоне» -> 7 раз нажмите на «номер сборки» или «версия miui»
2. В настройках для разработчиков активируйте отладку по USB.
3. Подключаем смартфон к ПК <mark style="color:purple;">оригинальным</mark> кабелем
4. При подключении USB кабеля выбираем «Передача файлов».
{% endtab %}
{% endtabs %}



### Проверка соединения

{% tabs %}
{% tab title="Текст" %}
1. Перейдите в раннее распакованную папку (`C:\adb`)
2. В ней, в адресной строке папки, сверху, напишите `cmd` и нажмите Enter. Откроется командная строка \[[видео](https://youtu.be/IPcTzLhBo38)]
3. Проверьте доступность устройства и правильность установки драйверов. Для этого выполните команду `adb devices`
   * Если драйвера успешно установлены и телефон подключен правильно - вы увидите следующий ответ: `<серийный номер устройства> device`
   * Если что-то неправильно, то в списке подключенных устройств (List of devices attached) будет пусто.
{% endtab %}
{% endtabs %}



### Полезные команды

| Действие                     | Команда                                                 |   |
| ---------------------------- | ------------------------------------------------------- | - |
| Удаление-Заморозка программы | adb shell pm uninstall -k --user 0 \*package name\*     |   |
| Восстановление программы     | adb shell pm install-existing --user 0 \*package name\* |   |

{% hint style="info" %}
<mark style="color:blue;">Полезное:</mark> \*package name\* можно узнать через «[Apk Inspector](https://play.google.com/store/apps/details?id=bg.projectoria.appinspector)»
{% endhint %}

{% hint style="success" %}
<mark style="color:green;">Подробнее:</mark> Другие [полезные команды ADB](https://4pda.to/forum/index.php?showtopic=383300\&view=findpost\&p=15982669\&anchor=Spoil-15982669-4)
{% endhint %}
