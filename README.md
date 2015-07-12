# elementary-style
Android icon theme.

<b>Добавление иконок в пак.</b>

1. Сконвертировать иконку в PNG (192px).

2. SVG положить в /icons-source/, PNG в /app/src/main/res/drawable-xhdpi/.*

3. Прописать название иконки в /app/src/main/res/values/drawable.xml.
Пример:

<code><item drawable="ru_superjob_client_android"/></code>

4. Прописать название иконки в /app/src/main/res/values/iconpack.xml.
Пример:

<code><item>ru_superjob_client_android</item></code>

5. Задать иконке класс приложения в /app/src/main/res/xml/appfilte.xml.
Пример:

<!-- File Explorer -->
    <item component="ComponentInfo{com.rhmsoft.fm/com.rhmsoft.fm.FileManager}" drawable="file_explorer"/>

Для удобства можно использовать http://czarnomorski.pl/search.php


* - имя иконки не должно содержать заглавных букв.
