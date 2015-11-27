# HeartRateRunner

![HeartRateRunner Screenshot Bright](/doc/HeartRateRunner1.png) ![HeartRateRunner Screenshot Dark](/doc/HeartRateRunner2.png)

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

## Future changes
* Time spend in heart rate zone