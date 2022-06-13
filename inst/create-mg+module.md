---
description: Расскажем, как создать простой модуль magisk
---

# Создание модулей Magisk

{% hint style="danger" %}
<mark style="color:red;">**Автор данной инструкции не несёт ответственности за ваши действия. Все ваши действия выполняются на ваш страх и риск.**</mark>
{% endhint %}

{% hint style="warning" %}
**Если вы сделаете некорректно работающий модуль magisk, то ваш смартфон может попасть в бутлуп**
{% endhint %}

{% hint style="warning" %}
#### Если ваш смартфон уже попал в бутлуп, вы можете удалить проблемный модуль через twrp данным способом <a href="#esli-vash-smartfon-uzhe-popal-v-butlup-vy-mozhete-udalit-problemnyi-modul-cherez-twrp-dannym-sposobo" id="esli-vash-smartfon-uzhe-popal-v-butlup-vy-mozhete-udalit-problemnyi-modul-cherez-twrp-dannym-sposobo"></a>
{% endhint %}

{% hint style="warning" %}
**Если даже после удаления модуля у вас остались некоторые проблемы в интерфейсе и прочим, то, к сожалению, вам может помочь только перепрошивка или сброс до заводских настроек**
{% endhint %}

{% hint style="warning" %}
**Модули могут нагружать систему вашего смартфона. Это означает, что если вы понаделаете много простых модулей и включите их в «magisk», то это может создать баги, глюки и зависания в вашем смартфоне.**
{% endhint %}



### Скачивание заготовки модуля

{% tabs %}
{% tab title="Текст" %}
1. Скачиваем модуль пустышку (в правой колонке «Файлы»)
2. Распаковываем скачанный архив.
{% endtab %}

{% tab title="Файлы" %}
{% file src="../.gitbook/assets/blank_magisk_module.zip" %}
{% endtab %}
{% endtabs %}

****

### Содержание архива

**Внутри мы видим два файла и одну папку:**

{% tabs %}
{% tab title="META-INF" %}
2.1 «META-INF» - это двигатель модуля. Она нужна для работы самого модуля. Эту папку трогать никогда не потребуется.
{% endtab %}

{% tab title="customize.sh" %}
«customize.sh» - в этом файле можно удалять приложения и прочее. Для того, что бы удалить приложение, нужно знать путь к нему в системном корне.



**«customize.sh» — код для удаления:**

```
REPLACE="
/«путь к файлу»
/«путь к файлу»
"
```

{% hint style="warning" %}
<mark style="color:orange;">Обратите внимание:</mark> На каждой прошивке пути в корне системы могут разниться!
{% endhint %}
{% endtab %}

{% tab title="module.prop" %}
«module.prop» - в этом файле содержится информация о самом модуле. Его желательно заполнять



**«module.prop» — что писать?**

```
id=Например, "mymodule"
name=Название модуля. Рекомендуется делать аналогично id.
version=Версия модуля. Например "1.0"
versionCode=Код версии. Например "1"
author=Автор
description=Описание
```

{% hint style="warning" %}
<mark style="color:orange;">**Внимание:**</mark>** ** Между знаком “=” и “данными” не должно быть пробела!
{% endhint %}

```
id=mymodule — Верно ✓
id = mymodule — НЕверно ×
```

{% hint style="success" %}
<mark style="color:green;">Рекомендация:</mark> Пиешите id и name одинаковыми
{% endhint %}

```
id=mytestmodule
name=mytestmodule
```



Пример module.prop:

```
id=mymodule
name=mymodule
version=1.1
versionCode=1
author=пепе
description=Модуль создан жабой пепе, для свинки пепе!
```
{% endtab %}
{% endtabs %}



### Создание простого модуля

> Для примера попробуем заменить звук блокировки и разблокировки смартфона.

{% hint style="info" %}
<mark style="color:blue;">Полезное:</mark> Звуки могут находиться по пути `/system/media/audio/ui` (У вас может быть другой путь) и имеют \*.ogg расширение
{% endhint %}

{% tabs %}
{% tab title="Текст" %}
1. Перейдем по пути `/system/media/audio/ui` и найдем интересующие нас звуки (скриншот 1)
2. Отлично, зная путь и оригинальное название файлов мы можем создать модуль.
   * В модуле заготовке:
     1. Создаем папку `system`&#x20;
     2. В папке `system` создаем папку `media` и так далее, воссоздавая оригинальный путь
     3. В папку ui переносим наши новые звуки и переименовываем их в соответствии с оригиналом (`Unlock.ogg` & `Lock.ogg`)
3. После воссоздания пути и файл настраиваем `module.prop` и наш модуль будет <mark style="color:green;">готов</mark> 👍

{% hint style="danger" %}
<mark style="color:red;">Внимание:</mark> При создании папок и переименовывании файлов соблюдайте строгий регистр (строчные и прописные буквы), иначе ничего не получится!
{% endhint %}
{% endtab %}

{% tab title="Скриншоты" %}
![Скриншот 1](https://telegra.ph/file/c9e51f5bcb2a1c2633fc4.jpg)

![Скриншот 2](https://telegra.ph/file/a3b8fcca8abdfe50f07da.jpg)
{% endtab %}
{% endtabs %}

***

### Итоги

> Вся эта инструкция - лишь вершина айсберга всего того, что можно сделать с модулем магиска, более подробно изучить всё это поможет вам такой замечательный сервис как [google.com](https://google.com/). Вся эта инструкция - лишь вершина айсберга всего того, что можно сделать с модулем магиска, более подробно изучить всё это поможет вам такой замечательный сервис как [google.com](https://google.com/).

***

### Аналог

{% hint style="info" %}
<mark style="color:blue;">Полезное:</mark> [Альтернативная инструкция с 4pda](https://4pda.to/forum/index.php?showtopic=946260\&view=findpost\&p=93425994)
{% endhint %}
