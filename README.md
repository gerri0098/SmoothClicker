# Smooth Clicker
_A free open-source easy to use material-designed autoclicker for Android rooted devices._

This app can trigger software clicks / touches thanks to system Shell commands executed in the system as SU.
The app is open-source, easy to use and to configure and can make several clicks with delayed starts and pauses between each click.
You can also repeat clicks sequences and make infinite clicks loops.
The app possesses a dedicated Android service you can reach and trigger to make some click processes instead of using the GUI.

_Why this app? Because I wanted to build my own auto clicker / auto touch to make some tricks on games or on apps (like <a href="https://play.google.com/store/apps/details?id=com.mlt.woy&hl=fr">Woy !</a>, <a href="http://orteil.dashnet.org/cookieclicker/">Cookie Clicker</a> or <a href="https://play.google.com/store/apps/details?id=com.supercell.clashofclans&">Clash of Clans</a>)._

The project contains the _Java 7_ sources, the _JavaDoc_ as HTML pages, the unit tests with _JUnit_ and _Robolectric_ and the instrumented tests with _Espresso_ and _UIAutomator_.

The app can be found in Google Play <a href="https://play.google.com/store/apps/details?id=pylapp.smoothclicker.android">here</a>, or with the following QR-Code :

<img src="https://github.com/pylapp/SmoothClicker/blob/master/qrcodes/SmoothClicker_PlayStore_QRCode.png" alt="QR Code to go to the Play Store" title="Flash to go to the Play Store" width="200"/>


***
## Screen shots
<table>
<tr>
<td>
<img src="https://github.com/pylapp/SmoothClicker/blob/master/dev/misc/pictures/ui_v2.0.0_en_framed/v2.0.0_en_intro_1.framed.png" alt="Introduction screen" title="Welcome to Smooth Clicker guys!" width="200">
</td>
<td>
<img src="https://github.com/pylapp/SmoothClicker/blob/master/dev/misc/pictures/ui_v2.0.0_en_framed/v2.0.0_en_clickeractivity_2.framed.png" alt="Set up the sequence of clicks you want to process" title="Set up the sequence of clicks you want to process" width="200">
</td>
<td>
<img src="https://github.com/pylapp/SmoothClicker/blob/master/dev/misc/pictures/ui_v2.0.0_en_framed/v2.0.0_en_multipoint_1.framed.png" alt="Select some points everywhere" title="Select some points everywhere" width="200">
</td>
</tr>
<tr>
<td>
<img src="https://github.com/pylapp/SmoothClicker/blob/master/dev/misc/pictures/ui_v2.0.0_en_framed/v2.0.0_en_multipoint_2.framed.png" alt="You can make long sequence of clicks to trigger" title="You can make long sequence of clicks to trigger" width="200">
</td>
<td>
<img src="https://github.com/pylapp/SmoothClicker/blob/master/dev/misc/pictures/ui_v2.0.0_en_framed/v2.0.0_en_settings.framed.png" alt="Settings can provide cool features" title="Settings can provide cool features" width="200">
</td>
<td>
<img src="https://github.com/pylapp/SmoothClicker/blob/master/dev/misc/pictures/ui_v2.0.0_en_framed/v2.0.0_en_credits.framed.png" alt="The app uses thir party libs !" title="The app uses third party libs !" width="200">
</td>
</tr>
</table>

***
## Features
* still need to have a rooted Android device...
* intro screen to introduce the app
* define a sequence of clicks to make
* several points can be selected
* random points can be selected
* a sequence of clicks can be repeated, endlessly if needed
* the unit time can be ms, s, m or h
* a delay can be defined before each sequence of clicks
* a pause can me made between each click
* device may vibrate on start and on each click
* device may display notifications when the process is on going, on clicks and when the countdown is running
* device may play a sound when a new click is done
* the configuration can be reset to defaults values
* a shake to clean feature can reset the configuration
* the configuration of the click process and the coordinates of the points to use can be saved/loaded in/from JSON files
* support for portrait / landscape modes, for tablets and handsets
* standalone mode with an empty activity loading points and config files before finishing and starting the click process
* standalone mode which can use these points and config files and a picture file which will trigger the click process if the device's screen matches this picture
* options which can force the screen to be on, keep it on, unlock it thanks to a dedicated Shell script to execute
* supported languages: english, french, russian, italian

***
## Licence
Under MIT License

***
## Warning
_Smooth Clciker_ is not maintained anymore, but feel free to fork the project and submit pull requests if you want.
Several steps I wanted to reach:
* replace not enough convenient AsyncTask by Background or Foreground services
* use design patterns (e.g. Mediator) to deal with the processes
* draw on the grid the selected points
* deal with landscape mode
* add shortcuts on app icons to start/stop processes
* trigger click process with physical buttons
* schedule clicks for dedicated dates or screenshots
* ...
