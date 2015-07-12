# elementary-style
Android icon theme.

<b>Добавление иконок в пак.</b>

* Исходная иконка SVG 48x48 в /icons-source. В название иконки должно быть присвоено согласно приложению в PlayMarket или самого приложения. Название не должно содержать кирилических символов и заглавных букв.

* Сконвертировать исходную иконку в PNG 192x192 и переместить в /app/src/main/res/drawable-xhdpi

* Задать иконке класс приложения в /app/src/main/res/xml/appfilter.xml.
Пример:
```
<item component="ComponentInfo{com.delphicoder.flud/com.delphicoder.flud.MainActivity}" drawable="com_delphicoder_flud"/>
```
Для удобства можно использовать http://czarnomorski.pl/search.php

* Прописать название иконки в /app/src/main/res/xml/drawable.xml.
Пример:
```
<item drawable="com_delphicoder_flud"/>
```
* Прописать название иконки в /app/src/main/res/values/iconpack.xml.
Пример:
```
<item>com_delphicoder_flud</item>
```
* Молиться и ждать ))

