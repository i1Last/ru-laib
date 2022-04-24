---
description: >-
  Расскажем, как использовать универсальный автоустановщик recovery. Для того
  чтобы использовать эту программу, достаточно иметь необходимое recovery с
  расширением *.img.
---

# Универсальный автоустановщик recovery

### Внимание

{% hint style="success" %}
**Qualcomm - протестировано, работает.**
{% endhint %}

{% hint style="warning" %}
**MediaTek - не протестировано, ставим на свой страх и риск.**
{% endhint %}

{% hint style="danger" %}
#### К сожалению, этот автоустановщик не стабилен, поэтому он может не работать на некоторых ПК и/или в некоторых случаях. <a href="#k-sozhaleniyu-etot-avtoustanovshik-ne-stabilen-tak-chto-on-mozhet-ne-rabotat-na-nekotorykh-pk-i-ili" id="k-sozhaleniyu-etot-avtoustanovshik-ne-stabilen-tak-chto-on-mozhet-ne-rabotat-na-nekotorykh-pk-i-ili"></a>
{% endhint %}

***

### Установка и использование

{% tabs %}
{% tab title="Текст" %}
1. Установите программу (колонка «Файлы»)
2. Установите [драйвера](../repo/drivers-pc.md)
   * [Как проверить работоспособность драйверов на ПК?](drivers-on-pc.md)
3. Заходите в программу и нажимайте «Выбрать recovery»
4. Найдите ваше «recovery.img» (если название вашего \*.img файла другое, то переименуйте его в `recovery`, чтобы у вас получилось `recovery.img`)
5. Нажимайте «Прошить recovery»
6. Ожидать окончания процесса, программа сделает все сама
{% endtab %}

{% tab title="Скриншоты" %}
![](https://telegra.ph/file/37dd16837610556e68790.jpg)
{% endtab %}

{% tab title="Файлы" %}
{% embed url="https://github.com/DaniilSkLi/RecoveryFlasher/releases/tag/1.1" %}
{% endtab %}
{% endtabs %}



### Возможные ошибки <a href="#oshibka" id="oshibka"></a>

* Если у вас вылезла ошибка по типу той, что на скриншоте ниже, то&#x20;

<details>

<summary>To run this application, you must install .NET Core. Would you like to download it now?</summary>

* Перейдите по ссылке и установите Desktop версию (Рекомендуется x86).
* Если это не поможет, попробуйте установить Console версию (Рекомендуется x86).
* Если и это не поможет, то к сожалению, ваш ПК <mark style="color:orange;">не поддерживает</mark> этот автоустановщик

</details>

***

### Подробнее о программе <a href="#podrobnee-o-programme" id="podrobnee-o-programme"></a>

{% embed url="https://github.com/DaniilSkLi/RecoveryFlasher#readme" %}
