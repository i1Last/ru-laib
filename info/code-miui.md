---
description: Расскажем схему построение названия прошивок и их архивов.
---

# Пояснение - названия MIUI

### **Прошивки MIUI:**

<details>

<summary>Stable (Стабильные)</summary>

#### 12**.5.2.0.RJUMIXM** <a href="#greater-than-or-12.5.2.0-rjumixm-or-less-than" id="greater-than-or-12.5.2.0-rjumixm-or-less-than"></a>

* 12 - головная версия MIUI
* 5 - подверсия MIUI
* 2 - основная версия MIUI
* 0 - мини версия MIUI
* R - версия android. [Подробнее](code-name-android.md)
* JU - индексное имя устройства. [Подробнее](code-name-devices.md)
* MI - регион прошивки \[MI; RU; EU; ID; IN; TW; CN]
* XM - код провайдера (XiaoMi)

</details>

<details>

<summary>Developer (Еженедельные)</summary>

#### MIUI 12 21.6.30

* 12 - головная версия MIUI
* 21 - год (2021)
* 6 - месяц (июнь)
* 30 - день месяца

</details>



### **Архивы прошивок:**

<details>

<summary>Fastboot</summary>

#### vayu\_ru\_global\_images\_V12.0.6.0.RJURUXM\_20210513.0000.00\_11.0\_global\_0f0301f619.tgz

* vayu - кодовое имя устройства. [Подробнее](code-name-devices.md)
* ru\_global - индекс прошивки. В китайских прошивках этот пункт отсутствует
* 12.0.6.0.RJURUXM - цифро-буквенный код прошивки. [Подробнее](code-miui.md#proshivki-miui)
* 20210513 - дата. ггггммдд
* 11.0 - версия android. [Подробнее](code-name-android.md)
* global - обозначет локаль. Для китайских - «cn»
* 0f0301f619 - первые 10 знаков хэш-суммы архива

</details>

<details>

<summary>Recovery</summary>

#### miui\_VAYURUGlobal\_V12.5.1.0.RJURUXM\_cfe292d16a\_11.0.zip

* VAYU - кодовое имя устройства. [Подробнее](code-name-devices.md)
* RUGLOBAL - индекс прошивки и его локаль
* 12.5.1.0.RJURUXM - цифро-буквенный код. [Подробнее](code-miui.md#proshivki-miui)
* cfe292d16a - первые 10 знаков хэш-суммы архива
* 11.0 - версия android. [Подробнее](code-name-android.md)

</details>

<details>

<summary>OTA</summary>

#### miui-blockota-vayu\_global-V12.5.2.0.RJUMIXM-V12.5.3.0.RJUMIXM-06cd04e32d-11.0.zip

* miui-blockota - означает, что это OTA прошивка
* vayu - кодовое имя устройства. [Подробнее](code-name-devices.md)
* global - индекс прошивки. В данном случае это MI
* V12.5.2.0.RJUMIXM - цифро-буквенный код прошивки, с которой должно осуществляться обновление. [Подробнее](code-miui.md#proshivki-miui)
* V12.5.3.0.RJUMIXM - цифро-буквенный код прошивки, на которую будет осуществляться обновление. [Подробнее](code-miui.md#proshivki-miui)
* 06cd04e32d - первые 10 знаков хэш-суммы архива
* 11.0 - версия android. [Подробнее](code-name-android.md)

</details>

<details>

<summary>Firmware</summary>

#### fw\_surya\_miui\_SURYAGlobal\_V12.0.9.0.QJGMIXM\_7f83537667\_10.0.zip

* fw - обозначает то, что это firmware архив. [Подробнее](firmware-is.md)
* surya - кодовое имя устройства. [Подробнее](code-name-devices.md)
* Global - индекс прошивки, откуда была взята firmware
* V12.0.9.0.QJGMIXM - цифро-буквенный код прошивки. [Подробнее](code-miui.md#proshivki-miui)
* 7f83537667 - первые 10 знаков хэш-суммы архива
* 10.0 - версия android. [Подробнее](code-name-android.md)

</details>
