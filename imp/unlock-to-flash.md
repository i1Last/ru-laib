---
description: Расскажем, что нужно сделать, чтобы с нуля прошить устройство.
---

# От разблокировки, до прошивки

{% hint style="info" %}
На данной странце мы покажем, что нужно делать, чтобы с нуля разблокировать загрузчик своего устройства и установить другую прошивку или root права.
{% endhint %}

***

### **1. Нужно подать заявку на разблокировку загрузчика**

* Выполняем <mark style="color:red;">**первый этап**</mark>** ** данной инструкции:

{% content-ref url="unlock-bootloader.md" %}
[unlock-bootloader.md](unlock-bootloader.md)
{% endcontent-ref %}

****

### **2. Ждем 168 часов (ровно неделя)**

* После подачи заявления на разблокировку загрузчика в большинстве случаев требуется ждать неделю.
* **Во время таймера **<mark style="color:red;">**нельзя**</mark>: _`обновлять прошивку, выходить из mi аккаунта, перепрошивать устройство через MiFlash`_

__

### **По прошествию недели**

****

### **3. Установка драйверов на ПК**

* Ставьте сначала первые. Если не заработают - ставим вторые и т.д.

{% content-ref url="../repo/draivera-dlya-pk.md" %}
[draivera-dlya-pk.md](../repo/draivera-dlya-pk.md)
{% endcontent-ref %}



### **4. Разблокируем загрузчик**

* Выполняем <mark style="color:red;">второй</mark> этап

{% content-ref url="unlock-bootloader.md" %}
[unlock-bootloader.md](unlock-bootloader.md)
{% endcontent-ref %}



### **5. Устанавливаем twrp через автоустановщик**

* Устанавливаем автоустановщик для вашего смартфона. Если нет для вашего устройства - берем из [4pda](https://4pda.to)

{% content-ref url="../repo/twrp-dlya-poco-x3-nfc-pro.md" %}
[twrp-dlya-poco-x3-nfc-pro.md](../repo/twrp-dlya-poco-x3-nfc-pro.md)
{% endcontent-ref %}



### **6. Прошиваем прошивку**

* Вся информация, как выбрать нужную из четырёх размещена сверху

{% content-ref url="flash/" %}
[flash](flash/)
{% endcontent-ref %}
