# elementary-style
Android icon theme.

<b>Добавление иконок в пак.</b>

1. Исходная иконка SVG 48x48 в /icons-source. В название иконки должно быть присвоено согласно приложению в PlayMarket или самого приложения. Название не должно содержать кирилических символов и заглавных букв.

2. Сконвертировать исходную иконку в PNG 192x192 и переместить в /app/src/main/res/drawable-xhdpi

3. Задать иконке класс приложения в /app/src/main/res/xml/appfilte.xml.
Пример:
```
<item component="ComponentInfo{com.delphicoder.flud/com.delphicoder.flud.MainActivity}" drawable="com_delphicoder_flud"/>
```
Для удобства можно использовать http://czarnomorski.pl/search.php

4. Прописать название иконки в /app/src/main/res/xml/drawable.xml.
Пример:
```
<item drawable="com_delphicoder_flud"/>
```
5. Прописать название иконки в /app/src/main/res/values/iconpack.xml.
Пример:
```
<item>com_delphicoder_flud</item>
```
6. Молиться и ждать ))

