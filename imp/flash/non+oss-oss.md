# non-OSS --> OSS

{% hint style="danger" %}
Прежде всего определите, есть ли такие прошивк вообще.
{% endhint %}

***

**1. Запуск TWRP**

* Полностью выключаем устройство
* Зажимаем кнопку питания и кнопку громкости вверх (+)
* Удерживаем до появления лого TWRP

***

**2. Делаем выборочную очистку**

* Раздел: Очистка
* Кнопка: Выборочная очистка
* Ставим галочки: **(Остальное не трогаем)**

> × Dalvik / ART Cache - кеш\
> × Data - все данные пользователя (Не путать с\
> внутреней памятью)\
> × Cache - кэш\
> \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
>
> \*× - ставим галочку

***

**3. Прошиваем Firmware** — \[подробнее]

> Обычно нужная версия fw пишется в описании прошивки.

* Раздел: Установить
* Ищите Firmware
* Нажимаете на него
* Делаете свайп снизу не трогая ничего остального

***

**4. Прошиваем прошивку**

* Раздел: Установить
* Ищите прошивку
* Нажимаете на неё
* Делаете свайп снизу не трогая ничего остального

***

**5. Прошиваем ядро - по желанию**

* Раздел: Установить
* Ищите ядро
* Нажимаете на него
* Делаете свайп снизу не трогая ничего остального

***

**6. Прошиваем GApps - по желанию**

> Они могут быть вшиты в прошивку изначально. Детально изучайте описание прошивки.

* Раздел: Установить
* Ищите GApps
* Нажимаете на них
* Делаете свайп снизу не трогая ничего остального

***

**7. Прошиваем magisk - по желанию**

* Раздел: Установить
* Ищите magisk
* Нажимаете на него
* Делаете свайп снизу не трогая ничего остального

***

**8. Прошиваем дешифратор - по желанию** — \[подробнее]

> Дешифратор необходимо прошивать каждый раз, даже при обновлении без format data.

* Раздел: Установить
* Ищите дешифратор
* Нажимаете на него
* Делаете свайп снизу не трогая ничего остального

***

**9. Форматирование DATA**

* Раздел: Очистка
* Кнопка: Форматировать DATA
* Вводим “yes” (без ковычек)

***

**10. Перезагрузка в OC**

* Раздел: Перезагрузка
* Кнопка: Система