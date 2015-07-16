# Theia Icon Theme
Android icon theme.

## RUS

<b>Как добавить иконку?</b>
* Убедитесь, что подходящая иконка для вашего приложения отсутствует в папке "icons-source"

* Если иконки нет, то создайте ее сами или сделайте запрос  в [Issues] (https://github.com/varlesh/elementary-style/issues)

Требования:

1. Общий стиль elementary

2. Исходный размер иконки в SVG размером 48x48, созданная в icons-source. (Название иконки должно быть присвоено согласно имени URL-ссылки в PlayMarket или самого приложения. Название не должно содержать кирилических символов и заглавных букв).

К примеру, приложение Flud.

Ссылка: https://play.google.com/store/apps/details?id=com.delphicoder.flud

Имя иконки: com_delphicoder_flud.svg

* Сконвертированная иконка в PNG размером 192x192, созданная в "app/src/main/res/drawable-xhdpi" с тем же именем, что и в "icons-source".
* Задать иконке класс приложения в "app/src/main/res/xml/appfilter.xml".
Пример:
```
<item component="ComponentInfo{com.delphicoder.flud/com.delphicoder.flud.MainActivity}" drawable="com_delphicoder_flud"/>
```
Для удобства можно использовать [DCikonZ Database] (http://czarnomorski.pl/search.php) или приложение [Activity Launcher] (https://play.google.com/store/apps/details?id=de.szalkowski.activitylauncher&hl=ru).

* Указать название иконки в "app/src/main/res/xml/drawable.xml".
Пример:
```
<item drawable="com_delphicoder_flud"/>
```
* Указать название иконки в app/src/main/res/values/iconpack.xml.
Пример:
```
<item>com_delphicoder_flud</item>
```
* Молиться и ждать :expressionless:

## ENG

<b>How to add icon?</b>
* Make sure that the appropriate icon for your application is not in folder "icons-source"

* If icon is not present, create it yourself or make a request in [Issues] (https://github.com/varlesh/elementary-style/issues)

Requirements:

1. Style elementary

2. Sorce SVG-file, size 48x48, established in "icons-source". (Icon name must be set according to the name of URL-links PlayMarket or the application itself. Name must not contain cyrillic characters and capital letters).

For example, an application Flud.

URL: https://play.google.com/store/apps/details?id=com.delphicoder.flud

Icon name: com_delphicoder_flud.svg

* Convert PNG icon size 192x192, established in "app/src/main/res/drawable-xhdpi" tems same name as in the "icons-source".
* Write class application icon in the "app/src/main/res/xml/appfilter.xml".
Example:
```
<item component="ComponentInfo{com.delphicoder.flud/com.delphicoder.flud.MainActivity}" drawable="com_delphicoder_flud"/>
```
For convenience, you can use [DCikonZ Database] (http://czarnomorski.pl/search.php) or app [Activity Launcher] (https://play.google.com/store/apps/details?id=de.szalkowski.activitylauncher&hl=ru).

* Write icon name in the "app/src/main/res/xml/drawable.xml".
Example:
```
<item drawable="com_delphicoder_flud"/>
```
* Write icon name in the "app/src/main/res/values/iconpack.xml".
Example:
```
<item>com_delphicoder_flud</item>
```
* Pray and wait :expressionless: