# elementary-style
Android icon theme.

<b>Добавление иконок в пак.</b>

1. Исходная иконка SVG 48x48 в /icons-source. В название иконки должно быть присвоено согласно приложению в PlayMarket илисамого приложения. Название не должно содержать кирилических символов и заглавных букв.

2. Сконвертировать исходную иконку в PNG 192x192 и переместить в /app/src/main/res/drawable-xhdpi

3. Прописать название иконки в /app/src/main/res/values/drawable.xml.
Пример:
```
ru_superjob_client_android
```
4. Прописать название иконки в /app/src/main/res/values/iconpack.xml.
Пример:
```
ru_superjob_client_android
```
5. Задать иконке класс приложения в /app/src/main/res/xml/appfilte.xml.
Пример:
```
<!-- Torrent -->
    <item component="ComponentInfo{com.delphicoder.flud/com.delphicoder.flud.MainActivity}" drawable="com_delphicoder_flud"/>
```
Для удобства можно использовать http://czarnomorski.pl/search.php
