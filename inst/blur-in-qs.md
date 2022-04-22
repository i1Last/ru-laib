---
description: >-
  Расскажем, как вернуть блюр вместо серого фона в центре управления на
  смартфонах под управлением MIUI.
---

# Размытие в центре управления

### При открытии центра управления у вас серый фон вместо красивого размытия? Исправим это. <a href="#pri-otkrytii-centra-upravleniya-u-vas-seryi-fon-vmesto-krasivogo-razmytiya-eto-legko-ispravit." id="pri-otkrytii-centra-upravleniya-u-vas-seryi-fon-vmesto-krasivogo-razmytiya-eto-legko-ispravit."></a>

{% tabs %}
{% tab title="Текст" %}
1. Скачиваем приложение «[Set Edit](https://play.google.com/store/apps/details?id=by4a.setedit22)» из Play Market
2. После установки программы - запускаем её
3. Ищем строку `deviceLevelList` и жмём на неё
4. В появившемся окне тыкаем по «Edit Value»
5. Заменяем значение на `v:1,c:3,g:3`
6. Жмём кнопку «Save Changes»
7. Что бы изменения пришли в силу, <mark style="color:purple;">необходимо перезагрузить смартфон</mark>
{% endtab %}

{% tab title="Скриншоты" %}
![](https://telegra.ph/file/3b268710338708b64ca4b.jpg)

![](https://telegra.ph/file/16a2fd72c2e2a92064f5c.jpg)
{% endtab %}
{% endtabs %}



### **Нет такой строки?**

1. Если её действительно нет, то просто создайте ее, нажав сверху на кнопку «Add new setting»
2. Далее введите название `deviceLevelList`
3. И последнее - введите значение:&#x20;

* Значение серой шторки:   ****   `v:1,c:2,g:1`
* Значение размытой шторки:   `v:1,c:3,g:3`
