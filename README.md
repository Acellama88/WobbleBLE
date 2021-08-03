# Wobble on Arduino Nano 33 BLE
## Introduction:
  The wobble is another in a long list of open-source DIY floating hydrometers designed to be left in beer while it ferments. This implementation leverages the capabilities of the Arduino Nano 33BLE communicate specific gravity and temperature readings through low power Bluetooth. The information is communicated via the iBeacon standard where specific gravity is in the primary variable and temperature in the secondary variable. This is identical to existing products in the market and can be read via their software. Data can also be read manually using any iBeacon scanner.


  There is a commercialized product that offers similar functionality currently on the market, but the design here offers a significant cost savings if you can complete the build. You will need some competency with soldering, 3D printing, and possible excel linear regression. Please note that the accuracy of the measurement will depend on quality of the build and your commitment to getting a high accuracy linear fit. If you are only interested in the level of fermentation activity, then no calibration is needed.
