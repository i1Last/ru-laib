---
description: Расскажем о самом минимальном способе починки SafetyNet.
---

# v24.x: Zygisk + DenyList

### **1. Активируем Zygisk и DenyList**

{% tabs %}
{% tab title="Текст" %}
1. Заходим в Настройки magisk
2. Включаем «Zygisk»
3. Включаем «Активировать DenyList»
{% endtab %}

{% tab title="Скриншоты" %}
![](https://telegra.ph/file/d4b4957a9002c3895d3fd.jpg)


{% endtab %}
{% endtabs %}

****

### **2. Настраиваем DenyList**

{% tabs %}
{% tab title="Текст" %}
1. Заходим в «Настройка DenyList»
2. Нажимаем на "три точки" справа сверху
3. Активируем пункт «Системные приложения»
{% endtab %}

{% tab title="Скриншоты" %}
![](https://telegra.ph/file/70d843813a17fa0b3eac8.jpg)


{% endtab %}
{% endtabs %}

****

### **3. Галочки**

{% tabs %}
{% tab title="Текст" %}


1. Находим «Google Pay»
2. Включаем все галочки у «Google Pay»
3. Находим «Сервисы Google Play»
4. Включаем следующие две галочки:

```
com.google.android.gms
com.google.android.gms.unstable
```
{% endtab %}

{% tab title="Скриншоты" %}
![](https://telegra.ph/file/2d0795b2336757812eb57.jpg)


{% endtab %}
{% endtabs %}

****

### **4. Перезагружаем устройство**

{% hint style="info" %}
Данное действие <mark style="color:orange;">обязательно</mark>. Достаточно выполнить самую обычную перезагрузку вашего устройства.
{% endhint %}

***

### **5. Очищаем данные Google**

{% content-ref url="google-clear.md" %}
[google-clear.md](google-clear.md)
{% endcontent-ref %}

***

### **6. **<mark style="color:green;">**Готово**</mark>** 👍**
