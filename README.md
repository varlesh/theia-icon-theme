# Theia Icon Theme

elementary-style icon theme for popular Android launchers.

##Preview
![Preview](http://40.media.tumblr.com/e6dd26e298c5a6ccac1df2cb82d3214c/tumblr_inline_nroq9ekTbM1tp1n7a_500.png)

##Installing
[![Available on F-Droid](http://storage1.static.itmages.ru/i/15/0718/h_1437239002_7516422_0f53ea8613.png)](https://f-droid.org/app/com.elementarytoday.theia)

##How to add icons

### RU

<b>Как добавить иконку?</b>
* Убедитесь, что подходящая иконка для вашего приложения отсутствует в папке `icons-source`

* Если иконки нет, то создайте ее сами или сделайте запрос  в [Issues](https://github.com/varlesh/elementary-style/issues)

Требования:

1. Общий стиль elementary

2. Исходный размер иконки в SVG размером 48x48, созданная в `icons-source`. (Название иконки должно быть присвоено согласно имени URL-ссылки в PlayMarket или самого приложения. Название не должно содержать кирилических символов и заглавных букв).

К примеру, приложение Flud.

Ссылка: https://play.google.com/store/apps/details?id=com.delphicoder.flud

Имя иконки: `com_delphicoder_flud.svg`

* Сконвертированная иконка в PNG размером 192x192, созданная в `app/src/main/res/drawable-xhdpi` с тем же именем, что и в `icons-source`.
* Задать иконке класс приложения в `app/src/main/res/xml/appfilter.xml`.
Пример:
```xml
<item component="ComponentInfo{com.delphicoder.flud/com.delphicoder.flud.MainActivity}" drawable="com_delphicoder_flud"/>
```
Для удобства можно использовать [DCikonZ Database](http://czarnomorski.pl/search.php) или приложение [Activity Launcher](https://play.google.com/store/apps/details?id=de.szalkowski.activitylauncher&hl=ru).

* Указать название иконки в `app/src/main/res/xml/drawable.xml`.
Пример:
```xml
<item drawable="com_delphicoder_flud"/>
```
* Указать название иконки в `app/src/main/res/values/iconpack.xml`.
Пример:
```xml
<item>com_delphicoder_flud</item>
```
* Молиться и ждать :expressionless:

### EN

<b>How to add an icon?</b>
* Make sure that the icon for your application doesn't exist under `icons-source` folder

* If the icon doesn't exist, create it and do a pull request or file a request for the icon in [Issues](https://github.com/varlesh/elementary-style/issues)

Requirements:

1. The icon must be in the same style as elementary OS icons

2. The icon must be in SVG format, icon size: 48x48. The icon must be placed to `icons-source`. (Name of the file must be the same as the PlayMarket application ID, without cyrillic or capital letters in the name)

For example, let's create an icon for Flud application.

The URL: https://play.google.com/store/apps/details?id=com.delphicoder.flud and the PlayMarket application ID is `com.delphicoder_flud`

In this case the name of the icon must be `com_delphicoder_flud.svg`

Now follow these steps:

* Convert the icon to PNG format, icon size: 192x192. Put the png icon to `app/src/main/res/drawable-xhdpi` (do not rename the icon, svg and png icons must have the same names)
* Set the class for the icon in `app/src/main/res/xml/appfilter.xml`.
Example:
```xml
<item component="ComponentInfo{com.delphicoder.flud/com.delphicoder.flud.MainActivity}" drawable="com_delphicoder_flud"/>
```
You can use [DCikonZ Database](http://czarnomorski.pl/search.php) or [Activity Launcher](https://play.google.com/store/apps/details?id=de.szalkowski.activitylauncher).

* Write the icon name to `app/src/main/res/xml/drawable.xml`.
Example:
```xml
<item drawable="com_delphicoder_flud"/>
```
* Write the icon name to `app/src/main/res/values/iconpack.xml`.
Example:
```xml
<item>com_delphicoder_flud</item>
```
* Pray and wait :expressionless:
