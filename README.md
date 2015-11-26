# HeartRateRunner

![RunnersField Screenshot Bright](/doc/HeartRateRunner1.png) ![RunnersField Screenshot Dark](/doc/HeartRateRunner2.png)

This is free a Data Field for the Fenix 3 that shows multiple values on a single field. 
RunnersField is open source and its code resides at github: https://github.com/roelofk/HeartRateRunner

===============================================

## Special thanks
* To Konrad Paumann
* Thank you for your hard work and making your code freely available!!!
* HeartRateRunner datafield is an addition to RunnersField
* RunnersField is open source and its code resides at github: https://github.com/kopa/RunnersField
* Release versions of RunnersField are published in the [Garmin App Store](https://apps.garmin.com/en-US/apps/8428701b-e621-4156-9d4e-37d92b30151f)

===============================================

## Feedback 

===============================================

## Features
* TIME: 12/24h mode based on system settings.
* PACE: pace in km/min or mi/min based on system settings (as average of the last 10 values).
* AVG PACE: average pace over the whole activity.
* DISTANCE: elapsed distance in km or miles based on system settings.
* DURATION: duration of the activity in [hh:]mm:ss
* GPS: green/blue bars for poor/acceptable/good signal, gray if no signal.
* battery: visualization of battery percentage as indicator bar. 
  If battery value is lower than 30 the indicator bar gets orange. If value is lower than 10% the exact value will be shown and the indicator bar turns red.
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

## Changelog 1.0.0
* Heart rate zone color arcs
* Heart rate zone indicator
* Heart rate zones are currently fixed:
* zone1 = 117;
* zone2 = 131;
* zone3 = 145;
* zone4 = 159;
* zone5 = 173;
* hrmax = 187;

===============================================

## Future changes
* Heart rate zone calculation
* Time spend in heart rate zone