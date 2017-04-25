# Android Things
Android Things is a device-based OS for Internet of Things. It helps to build rapid prototypes of connected devices with the ease and power of Android.

## Android-Things-On-Intel-Edison
This repository is created to offer step-by-step procedure to get started with Android Things on Intel Edison to build connected devices for a wide variety of consumer, retail, and industrial applications. It has (almost) no dependencies and is designed for developers from Beginners to Intermediate level.

## 1. Setup
You can setup this project in your local machine by cloing this repository or downloading the zip file.

## 2. Downloads & Installations
* Download [Latest preview of AndroidThings_Edison_DevPreview](https://developer.android.com/things/preview/download.html) Non-OS image to flash Android Things on Intel Edison
* Download [Installer](https://software.intel.com/en-us/iot/hardware/edison/downloads) to access the features in the IOT Developer kit
* Download and Install [Intel Platform Flash Lite tool](https://01.org/android-ia/downloads/intel-platform-flash-tool-lite)
* Download and Install [Android Studio](https://developer.android.com/studio/index.html)

## 3. Flashing

Before starting to flash, keep the swicth on the board in the position towards the micro-USB ports.

<p align="center"><img src="https://lh3.googleusercontent.com/QD81nRntD-q5fwx-AHfEbpJn53LC5EMR3m29Q47XhC47iZcauaSjMSZeHi-jdVhwoH7Vl5-aRbnn-fw0pqz_uvbOr8odHupSB32Ejz3xKeOxvQRcG4y4JLEFDnCXYOZBTTyI-5lBlavZjge6OJBFKWja38eOJlgRKVGIfkbqOO9iaWkmyaQfG0vB2X3rbGGPSpAFOI31IsbRloZQDA6KF-V5dyndgdgToVQwyoyvBl8wEwyhghfb97ZlBmiihq9Ta1eai4iooqelucVl_eb4RpfWpjA5Hbs15uxRBcQDu-8BmJ7ilp69T0wOnF8l2nQ9Y_u36gMiWS6lzEjvdNM1XZbeIkS0W2vj4atWEs67SkYw4jBntjXW4OhzX2xOz0cNCl4zjI8bDIS6XWpyz1TLiaz5LHq491RCOzI8XWUtAH3VBPRl3cTUTaK8Rcbe66xb94vmc1t3un1-CsBJJqwrtR_DAS-RdGM3DFRf-iVMpEpdai9o-gvQjwLvOcWgDM5lEbweeYQiwM_3_viosnBYeX8oS8atTWSyJJdm2sSUoq1jPsbNnCrAkIY96lhFAQUoJfk4pc4_WHN21TZWXu9ukr7b9Yk8tsiNsZmgPSvFLFZFgihTkq4RcA=w1930-h1136-no" alt="Intel Edison" align="center" height="50%" width="50%"></p>

Open Intel Platform Flash Lite tool to flash the following images:
* Flash Yocto Poky image on Intel Edison

<p align="center"><img src="https://lh3.googleusercontent.com/ALlWNfysJKHTh8NYQr4SASUf56NNxeEa7vnvPxJX4IFVx07SVlqgk1V5p9SQdatjgbRk7DRbX7zgkdkfiORxt9Snk2bIMMf5UVSWlVO8X5oFAnzqgs_pO4iHRK0VPrAwTVEre4VEhOLID-F9Lst3_lVrn_97exmgK_1X72fidSert8aqHuE7PixloyCHxXZj_4fQb-BhAFsMg15FRuuRJzyboI_Y6sAeDdDYeXrTAjRxFvZEfJBZxtsxB4gXFM7j4DIFZGoILoStBkRv31RLYwRFeJ3_1ni_KPtfq3Ye3MJyHLAHhJf0KeauB0-OHNNJi3xdnR-JBrcxzk4Q1WmwwrVE2S1DmrECKlTi8yEmm1LaT-jg-V3TmK5uT9ykw7BxaEx3gziL6ywLta0xuJhYBsmY-BG_MNpmOkxU-l7FqLAR77pJLdEQPSzyzOnvyCBzGFQze55M-KFd_D-LKG-ktosSkjyZbMZOKbV7Qkgj6qW4HBIcNduAhdIaGtky81yU_1VYgcBfNRuPloXDLt9frBo-H6w2fAx2H4C1llfoy8LTAKO1tfSdGGsjB3pwNvRhGuuveh-TbAsMydnCEDJcPvw3MxHaKhaZ9Z9znHcsv6bZdl1S0hmlNw=w479-h369-no" alt="Platform Flash Lite tool" align="center" height="50%" width="50%"></p>

To flash Android Things onto Intel Edison, press the combination of keys as follows:
* Press FW button on Intel Edison's Arduino breakout board
* Insert the cable to the OTG port and then release the FW button and then flash it using the Platform Flash lite tool
* In the Platform Flash Lite tool, select configuration as 'Non_OS' and flash the latest preview of AndroidThings_Edison_DevPreview on Intel Edison

<p align="center"><img src="https://lh3.googleusercontent.com/eVF-ChkHcYnP5fsimtbFj6RUp8YIaaaJ-SImUjDe51JE0mIRQGV8Y0bsiEyDzK_d5VY-Nm_y9bkPwY4cWxcKneD-obg31vVnOv6zMk8It_wecoDaIPeO1ECHHRNtYeuX13qkBl8VEOqkgDkcvlfza3CBYL1yYZzbm9A2OldmvsmtxUjfjhZVr5eAVnO2DLSGi3ZvjNXYz_4ezqom7FYWJFJpXLogg5QUJwBExEpBxHX71NJ-EgiltBWPzTfLI2PJ4TDAcqRyamz1EM9lSyw7KM9x9p8HDAHf7R4bUc1NevH7zOhq8dhJrXaMSQ7vulBZbTgs89cmR20vYTGWQnKWzb3KWuo8hxgEu1Z4ZMxV_bs793AidK1mBuC9BnTkpk-3bHAg5huILHOsH5JMYcrxdW7FyaEbot9t-aSrCsZDf4iZgYXkGWgFmJ06o6soNI7ZJy7EOjQYsVYNwALG_gUuB2w89J-0tjdx4b1seShqr9kOnLWchetTdMnTLZlZGLnIjgVnZ8b09PbL6a6Js5MCr0gm8EopCIgIwic9kb1XeowmJNmt48F1Hy5gOt4d--oVUtuVYB7gSRTS3HwdckdbuoQxDAk7mMgb0EwBc-i3TwFc3OmkJ28O5w=w622-h334-no" alt="Intel Edison" align="center" height="50%" width="50%"></p>

Once flashed, enter into the androidthings_edison_devpreview directory and use fastboot to flash system images:
```sh
$fastboot devices

$fastboot \
    flash gpt partition-table.img \
    flash u-boot u-boot-edison.bin \
    flash boot_a boot.img \
    flash boot_b boot.img \
    flash system_a system.img \
    flash system_b system.img \
    flash userdata userdata.img \
    erase misc \
    set_active _a

$fastboot \
    flash gapps_a gapps.img \
    flash gapps_b gapps.img

$fastboot \
    flash oem_a oem.img \
    flash oem_b oem.img
```

Once flashed, reboot the device to enter into adb mode:
```sh
$fastboot reboot
```
Upon reboot, check if the device (Intel Edison with Android Things) is detected as android device and detected by the following command:
```sh
$adb devices
```

In case, you're unable to start the adb daemon, restart the adb server as:
```sh
$adb kill-server
$adb start-server

$adb devices
```

## 4. Configurations
After flashing the board, we'll connect the board with internet using adb.

#### Connecting Wi-Fi:
To achieve this, get the SSID and password of the Wi-Fi and execute the following commands:
```sh
$adb shell am startservice \
    -n com.google.wifisetup/.WifiSetupService \
    -a WifiSetupService.Connect \
    -e ssid <Network_SSID> \
    -e passphrase <Network_Passcode>
```

## 5. Development
Want to contribute? Great! We're expanding features such as adding voice commands to contol things from Android App. Keep watching this space.

Meanwhile, you can contribute to this by:
* Filing issues
* Contributing Code
* Contributing Feature
* Please contact the author for more information on contributing

## 6. License

MIT Licensed


## 7. Author
Anuj Duggal ([LinkedIn](https://in.linkedin.com/in/anujduggal21) | [Twitter](https://twitter.com/AnujDuggal21) | [Facebook](https://www.facebook.com/AnujDuggal88))
