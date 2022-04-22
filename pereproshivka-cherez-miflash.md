# Перепрошивка через MiFlash

### Перепрошивка через MiFlash 

[Last](https://t.me/i1Last)\


:: Чтиво «АЛИСА» --> Инструкции --> [Перепрошивка через MiFlash](broken-reference) ::

***

**1. Скачиваем MiFlash на ПК.**

* Всегда [скачиваем последнюю версию MiFlash](https://xiaomiflashtool.com)

> В инструкции будет фигурировать версия — «MiFlash20210226»

***

**2. Открываем MiFlash.**

ᅠПри первом открытии у вас выползет окно с просьбой установки драйверов. Нажимайте кнопку «Install» и ожидайте окончания установки.



ᅠПосле окончания установки, у вас может появиться китайское меню. На нём написано (в переводе с кит. на рус.): „Установка завершена”. Нажимайте «OK» и закрывайте все окна связанные с драйверами.



***

**3. Скачиваем прошивку на ПК.**

* [Заходим на данный сайт](https://mirom.ezbox.idv.tw/en/phone/)
* Находим своё устройство
* Ищем нужный регион и версию
* Скачиваем архив в формате \*.tgz



***

**4. Открываем и разархивируем архив.**

1. В корне диска C (C:\\) создаем папку adb
2. Открываем скачанный \*.tgz архив в WinRAR или любой другой подобной программе
3. Распаковываем по пути «C:\adb\»
4. По окончанию распаковки заходим в MiFlash

***

**5. Подготовка к перепрошивке.**

**На смартфоне:**

1. Полностью выключаем
2. Зажимаем кнопку питания и кнопку громкости вниз (-)
3. Удерживаем до появления лого зайца, который копается в роботе
4. Подключаем к ПК (желательно оригинальным кабелем)

**На ПК:**

1. В MiFlash нажимаем кнопку «select» и выбираем нашу распакованную папку по пути «C:\adb\»



***

**6. Перепрошивка.**

* В MiFlash нажимаем кнопку «refresh»
* Ожидаем появления нашего устройства в списке
* Выбираем режим перепрошива:

> clean all — удаляет все данные с устройства (**рекомендуется именно этот способ**)

> save user data — сохраняет все данные на устройстве

> clean all and lock — удаляет все данные с устройства и блокирует загрузчик (**по умолчанию будет выставлен этот вариант, будьте внимательны!**)



* По завершению выполнения всех вышеперечисленных пунктов нажимаем кнопку «flash»
* Начнется прошив прошивки



***

**7. Окончание.**

* По завершению процесса перепрошивки вы можете отключить смартфон от ПК и запускать сам смартфон
* Учтите, что первый запуск любой прошивки будет дольше, чем последующие. Поэтому не бойтесь, если лого MIUI будет висеть 5 минут.
* Беспокоиться можно тогда, когда происходит следующее: Лого POCO > лого MIUI > лого POCO > лого MIUI — это называется бутлуп. Исправляется в большинстве случаев простым сбросом до заводских настроек. Это можно сделать в стоковом рекавери с помощью хард ресета