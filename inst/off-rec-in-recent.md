---
description: Расскажем, как отключить рекомендации в меню недавних.
---

# Отключение рекомендаций в меню недавних

{% hint style="danger" %}
<mark style="color:red;">**Автор данной инструкции не несёт ответственности за ваши действия. Все ваши действия выполняются на ваш страх и риск.**</mark>
{% endhint %}

### **Как отключить / включить?**

{% tabs %}
{% tab title="Текст" %}
1. Скачиваем [SetEdit](https://play.google.com/store/apps/details?id=by4a.setedit22) из Play Market
2. Заходим в него
3. Ищем и нажимаем на нужную строку
4. Нажимаем «Edit Value»
5. Выставляем значение — `1 = вкл.` / `0 = выкл.`
6. Нажимаем «Save Changes»
{% endtab %}

{% tab title="Скриншоты" %}
![](https://telegra.ph/file/509cf11fc66c3174d8959.jpg)
{% endtab %}
{% endtabs %}



### **Какие нужны строки?**

{% tabs %}
{% tab title="Текст" %}
`miui_recents_show_recommend` — показ рекомендаций в меню недавних приложений (#1 на скриншоте в правой колонке)

`miui_recents_show_mem_info` — показ состояния оперативной памяти в меню недавних приложений (#2 на скриншоте в правой колонке)
{% endtab %}

{% tab title="Скриншоты" %}
![](https://telegra.ph/file/c0b1cad2b4c1a997238ce.jpg)
{% endtab %}
{% endtabs %}

***

### **Что делать, если нет такой строки?**

1. Если её нет, то создайте ее, нажав сверху на кнопку «Add new setting»
2. Далее введите название `user_refresh_rate`
3. И последнее - введите значение:
   * `miui_recents_show_recommend` - рекомендации \[1]
   * `miui_recents_show_mem_info` - информация о памяти \[2]
