---
description: Расскажем, что такое vendor и какие vendor'ы бывают.
---

# Пояснение - Vendor

### Кратко и понятно:

> Vendor - это файлы, которые содержат в себе оптимизацию для устройства. Как правило самым оптимизированным вендором является CAF, за ним OSS и уже после MIUI (non-OSS) vendor.

****

### **Более подробно:**

> Vendor - это файлы, которые содержат оптимизацию для вашего устройства. В устройствах Xiaomi такой вендор именуется как MR / MQ (M-miui ; R - android R\[11]). MIUI вендор самый обычный. Он нормальный, но не лучший из возможных, поэтому появились OSS vendor и CAF vendor. OSS как правило более оптимизированный, а CAF еще более оптимизрован. OSS создается с нуля обычным человеком, как и CAF, однако для создания CAF вендора используются наработки оптимизации чипмейкера (Qualcomm SnapDragon), поэтому они оптимизированее, чем OSS и MIUI, но прошивок на таком вендоре мало.

****

### Разновидности vendor'а

{% tabs %}
{% tab title="MIUI (non-OSS) vendor" %}
#### Расшифровка

* MQ - MIUI Q
* MR - MIUI R



Как мы можем знать, Q и R - это кодовые названия android 10 и 11 соответственно ([Подробнее](code-name-android.md)). Из этого мы можем сделать вывод, что со временем появятся MS (А12), MT (А13) и т.п. вендоры.
{% endtab %}

{% tab title="OSS vendor" %}
OSS vendor - это кастомный вендор от мейнтейнеров (обычных людей-разработчиков)

[Подробнее про OSS](oss-is.md)
{% endtab %}

{% tab title="CAF vendor" %}
CAF vendor - кастомный вендор, которые создали мейнтейнеры с применением последних технологий от Qualcomm. Он является улучшенным OSS вендором и более оптимизированным, чем все остальные.
{% endtab %}
{% endtabs %}
