# Heart Rate Runner

![HeartRateRunner Screenshot Bright](/doc/HeartRateRunner5.png) ![HeartRateRunner Screenshot Dark](/doc/HeartRateRunner6.png)

Shows heart rate color arcs with a heart rate indicator.
This is free a Data Field for the Fenix 3 that shows multiple values on a single field. 
Heart Rate Runner is open source and its code resides at github: https://github.com/roelofk/HeartRateRunner

Release versions of Heart Rate Runner are published in the [Garmin App Store](https://apps.garmin.com/nl-NL/apps/cb7742e6-1914-490f-b581-fa41ad863b72)

===============================================

## Special thanks
* To Konrad Paumann
* Thank you for your hard work and making your code freely available!!!
* Heart Rate Runner datafield is an addition to RunnersField
* RunnersField is open source and its code resides at github: https://github.com/kopa/RunnersField
* Release versions of RunnersField are published in the [Garmin App Store](https://apps.garmin.com/en-US/apps/8428701b-e621-4156-9d4e-37d92b30151f)

===============================================

## Feedback 

===============================================

## Features
* HEART RATE: shows five colored zones. Zone is made thicker when in zone and indicator shows where in the zone you are.
* HEART RATE SETTINS: you can set your own zones in settings
* TIME: 12/24h mode based on system settings.
* PACE: pace in km/min or mi/min based on system settings (as average of the last 10 values).
* AVG PACE: average pace over the whole activity.
* DISTANCE: elapsed distance in km or miles based on system settings.
* DURATION: duration of the activity in [hh:]mm:ss
* use bright or dark color scheme based on the background color setting of the app (Settings/Apps/Run/Background Color).
  needs at least a firmware with SDK 1.2 compatibility (otherwise bright scheme is always used).

===============================================

## Install Instructions
A Data Field needs to be set up within the settings for a given activity (like Run)

* Long Press UP
* Settings
* Apps
* Run
* Data Screens
* Screen N
* Layout
* Select single field
* Field 1
* Select ConnectIQ Fields
* Select HeartRateRunner
* Long Press Down to go back to watch face

===============================================

## Usage
Start Run activity.
Hopefully you see the HeartRateRunner datafield and can read the values.

===============================================

## Changelog 1.2.2

* Moved Time to center

## Changelog 1.2.1
* Minor change to heartrate indicator making it more precise
* Hard set background of heartrate and time to black because of readability issues in inverse mode
* Added some screenshots, showing settings and that the app can be deleted through Garmin connect app

## Changelog 1.2
* Heart rate zones can now be set trough settings
* Had to remove gps indication because of memory issues

## Changelog 1.1
* Heart rate better visualization (white on black) on bottom center
* Added time in heart rate zone top center
* Improved memory print
* Removed battery and gps visualization in service of memory and time spend in heart rate zone

## Changelog 1.0.3
* Fixed an error

## Changelog 1.0.2
* Heart rate indicator better accuracy

## Changelog 1.0.1
* Heart rate zone indicator now black with white edges, hopefully better visible
* Heart rate zones are calculated with age: hrmax = 217 - (0.85 × age)
* zone1 = maxHr * 0.64; 
* zone2 = maxHr * 0.72; 
* zone3 = maxHr * 0.79; 
* zone4 = maxHr * 0.87;
* zone5 = maxHr * 0.94;
* hrmax = 217 - (0.85 × age);

===============================================