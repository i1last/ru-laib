# Что такое дешифратор (DFE)?

### Что такое дешифратор (DFE)? 

[Last](https://t.me/i1Last)\


:: Чтиво «АЛИСА» --> Знания --> [Что такое дешифратор (DFE)?](broken-reference) ::

***

**DFE - Disable Force Encryption или по обычному дешифратор.**

* Он нужен для того, что бы отключить принудительное шифрование на прошивках на основе AOSP. То есть он не дает зашифроваться вашему внутреннему хранилищу.

**Что будет, если моё внутреннее хранилище зашифруется?**

ᅠОтвет прост. Внутри вашего рекавери вы не сможете ни просматривать, ни редактировать, ни использовать файлы во внутреннем хранилище. Ваше рекавери просто не сможет его считывать, а это затрудняет использование самого рекавери.\
ᅠЕсли внутреннее хранилище зашифруется, то это никак не коснется SD-карты. Вы так же сможете продолжать просматривать и использовать файлы находящиеся на ней.

**Как прошить дешифратор?**

* Как обычно. Это делается при перепрошивке на (к примеру) ArrowOS.
* Если вышло обновление Arrow OS и вы желаете её обновить, то дешифратор **потребуется прошивать повторно.**
* Так же дешифратор нужно обязательно прошивать только после прошивки самой прошивки. Если прошить сначала дешифратор и только потом прошивку, то ничего хорошего из этого не выйдет.

**Подведем итог:**

ᅠШифрование нужно для сохранности ваших данных, но оно не удобно, если вы постоянно меняете прошивку.\
ᅠШанс того, что ваши данные украдут равен шансу того, что ваш смартфон украдут.

**В дополнение:**

ᅠБывают определенные рекавери, которые не требуют использование дешифратора, так как они самы способны расшифровывать хранилище. Однако такие рекавери бывают не везде и не сразу. Придется подождать, прежде чем такие появятся для вашего устройства.