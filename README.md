This application is now available on Google Play at
<https://play.google.com/store/apps/details?id=ca.farrelltonsolar.classic>

Classic Monitor is a free status monitor for Midnite solar 's, Classic 150, 200, 250 Charge Controller (www.midniteSolar.com). It is a Read Only Program, it does not write to the Classic.

The software is provided "AS IS", WITHOUT WARRANTY OF ANY KIND, express or implied.

Classic Monitor is NOT a product of Midnite solar, nor do they support this application!

If the app detects a Whizbang Junior current monitor, the State Of Charge will display along with a bi-directional current gauge.

Basic support for the Tristar MPPT charge controller from Morningstar is also included.

This application requires an Android device with at least API level 14 (Android 4.0 "Ice Cream Sandwich") 

## License
```

 Copyright (c) 2014. FarrelltonSolar

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.

```


Release notes:

-----------------

version 2.0

Transfer to code to Github
Added support for multiple classics using navigation drawer.
Re-design of classic detection using UDP broadcasts.
Added temperature gauges.
Implemented calendar, day & hour chart using native code rather than webview.
Added info and message tabs.
Implemented new Android sliding tab view pager.
Re-design gauge component to support latest Android 5.0 API 21.
Added auto-scale feature to gauges.
Updated French, Italian, Spanish localization resources

-----------------

version 1.7

Prepare for deployment to google play


-----------------

version 1.6

Added french localization resources

-----------------

version 1.5

Added chart view.
Implemented upload to PVOutput.org.

-----------------

version 1.4

Added data feed to calendar view.
Close TCP socket when app is minimized, re-open when app is resumed.

-----------------

version 1.3

Refactores code to use BroadcastIntents.
Modbus Master now running as an Android IntentService.
Added Custom modbus read for File transfer.
Gauge scaled by touching the gauge when unlocked.
Added SOC% on main page
Added 'Countertop' view for SOC%, activated by touching SOC% on main page
Added Webview for PVOUtputs and Calendar (data feeds not complete)
Added Aux LEDs to power gauge

-----------------

version 1.2

Added basic support for WhizBangJr, Battery Gauge is bi-directional if whizbangJr is detected.
Added placeholder for WhizbangJr AH data

-----------------

version 1.1

Added tabbed views.
Added Placeholder for Calendar and Chart pages
Fixed J2Mod IsConnected, no longer sending extra blank byte over TCP.

-----------------

version 0.2

Fixed crash at first startup.
Default scan range when no gateway detected.
catch J2MOD Exception and reconnect.
Added support for API level 10+
Added Gauge scale settings 
Added IP Scan range
Now uses J2ModLite.