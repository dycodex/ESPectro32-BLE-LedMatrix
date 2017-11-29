# ESPectro32-BLE-LedMatrix

A PlatformIO-based example to send text from compatible mobile app to ESPectro32 over Bluetooth, and then display the text on on-board ESPectro32's Led Matrix

## Mobile App
In order to send the text over Bluetooth, I use Bluefruit app. Download it here: [Android](https://play.google.com/store/apps/details?id=com.adafruit.bluefruit.le.connect&hl=en) or [iOS](https://itunes.apple.com/us/app/adafruit-bluefruit-le-connect/id830125974?mt=8).

## Run
You should have PlatformIO installed first. Then:
* Simply clone this repo
* Open Terminal/console, change directory to this folder
* Type `pio run` to build, or directly build and upload by typing `pio run -t upload`
* Check the message on serial by typing `pio devices monitor -b 115200`. Wait until this message ``

## Using App
Open Bluefruit app. Then: 

View device list, connect to `ESPectro32 LED Matrix` |  Tap `UART` | Type message and Send
:-------------------------:|:-------------------------:|:-------------------------:
![Step1](https://github.com/dycodex/ESPectro32-BLE-LedMatrix/raw/master/assets/app1.png)  |  ![Step2](https://github.com/dycodex/ESPectro32-BLE-LedMatrix/raw/master/assets/app2.png)  |  ![Step3](https://github.com/dycodex/ESPectro32-BLE-LedMatrix/raw/master/assets/app3.png)

Result:

![Result](https://github.com/dycodex/ESPectro32-BLE-LedMatrix/raw/master/assets/result.gif) 

That's it. Good luck.
