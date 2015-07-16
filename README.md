# elementary-style
Android icon theme.

<b>Как добавить иконку?</b>
* Убедитесь, что подходящая иконка для вашего приложения отсутствует в папке icons-source

* Если иконки нет, то создайте ее сами или сделайте запрос  в [Issues] (https://github.com/varlesh/elementary-style/issues)

Требования:

1. Общий стиль elementary

2. Исходный размер иконки в SVG размером 48x48, созданная в icons-source. (В название иконки должно быть присвоено согласно имени URL-ссылки в PlayMarket или самого приложения. Название не должно содержать кирилических символов и заглавных букв) К примеру, приложение Flud.

Ссылка: https://play.google.com/store/apps/details?id=com.delphicoder.flud

Имя иконки: com_delphicoder_flud.svg

* Сконвертированная иконка в PNG размером 192x192, созданная в /app/src/main/res/drawable-xhdpi  стем же именем, что и в icons-source.
* Задать иконке класс приложения в app/src/main/res/xml/appfilter.xml.
Пример:
```
<item component="ComponentInfo{com.delphicoder.flud/com.delphicoder.flud.MainActivity}" drawable="com_delphicoder_flud"/>
```
Для удобства можно использовать [DCikonZ Database] (http://czarnomorski.pl/search.php) или приложение [Activity Launcher] (https://play.google.com/store/apps/details?id=de.szalkowski.activitylauncher&hl=ru).

* Указать название иконки в app/src/main/res/xml/drawable.xml.
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