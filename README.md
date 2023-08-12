NoCost_NoAd_Scanner
===============

This is a similar application to that of OpenNoteScanner.
Since OpenNoteScanner is no longer supported by current andriod versions, this application, which has the same spirit - aims to provide pdf scanning services at no cost and without any ads.

This little application provides a way on scanning handwritten notes and printed documents.

It automatically detect the edge of the paper over a contrastant surface.

After the page is detected, it compensates any perspective from the image adjusting it to a 90 degree top view and saves it on a folder on the device.

It is also possible to launch the application from any other application that asks for a picture, just make sure that there is no default application associated with this action.

Screenshots
-----------

[![screenshot1](http://i.imgur.com/1MDisD3m.jpg)](http://imgur.com/a/ypytF/embed#0)
[![screenshot1](http://i.imgur.com/ksvmOlym.png)](http://imgur.com/a/ypytF/embed#3)
[![screenshot1](http://i.imgur.com/Ayy8GGgm.jpg)](http://imgur.com/a/ypytF/embed#1)
[![screenshot1](http://i.imgur.com/tzMLas3m.jpg)](http://imgur.com/a/ypytF/embed#2)

Requirements
------------

Because of the version of OpenCV that is used in the project it needs to run on Android 5.0 (lollipop) or newer.



How to Install
--------------



Instructions for building
-------------------------


### Command Line

Go to your base folder and import it using ```git```:

```
$ git clone https://github.com/Jacob-Lazar/NoCost_NoAd_Scanner.git
```

You need to point the environment variable ```ANDROID_HOME``` to your Android SDK folder and run ```gradle``` to build the project:

```
$ cd NoCost_NoAd_Scanner
$ export ANDROID_HOME=~/android-sdk-linux
$ ./gradlew assembleRelease
```

Instructions for Contributing
-------------------------
Feel free to fork the project and send us a pull request.

Contributing
------------

If you have any idea, feel free to fork it and submit your changes back to me.

Thanks
------

### Contributors


Most translations contributions are listed on [CONTRIBUTORS.md file](https://github.com/ctodobom/OpenNoteScanner/blob/master/CONTRIBUTORS.md) and code contributors are listed on [the Changelog file](https://github.com/ctodobom/OpenNoteScanner/blob/master/CHANGELOG.md) and [the commits history](https://github.com/ctodobom/OpenNoteScanner/commits)

Other people helped submitting [Issue Reports](https://github.com/ctodobom/OpenNoteScanner/issues) and giving info through the [Telegram Group](https://t.me/OpenNoteScanner). Their help is appreciated as well.

### External code

This application wouldn't be possible without the great material produced by the community. I would like to give special thanks to the authors of essencial parts I've got on the internet and used in the code:

* [Android-er / GridView code sample](http://android-er.blogspot.com.br/2012/07/gridview-loading-photos-from-sd-card.html)
* [Android Hive / Full Screen Image pager](http://www.androidhive.info/2013/09/android-fullscreen-image-slider-with-swipe-and-pinch-zoom-gestures/)
* [Adrian Rosebrock from pyimagesearch.com for the excellent tutorial on how to handle the images](http://www.pyimagesearch.com/2014/09/01/build-kick-ass-mobile-document-scanner-just-5-minutes/)
* [Gabriele Mariotti / On how to implement sections in the RecyclerView](https://gist.github.com/gabrielemariotti/e81e126227f8a4bb339c)


License
-------

Copyright 2023 - Jacob Lazar

Software licensed under the GPL version 3 available in GPLv3.TXT and
online on http://www.gnu.org/licenses/gpl.txt.

Use parts from other developers, sometimes with small changes,
references on autorship and specific licenses are on individual
source files.
