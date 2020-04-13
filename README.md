# iFakeLocation中文汉化版

![](https://i.imgur.com/ELFifkA.png)

## 系统环境要求:
### Windows:
* .NET Framework 4.5 or newer (pre-installed on Windows 8 & Windows 10)  
  https://dotnet.microsoft.com/download/dotnet-framework

* iTunes (Microsoft Store version or Win32/Win64 is fine)  
  https://www.apple.com/itunes/download/
  
### Mac OSX:
* .NET Core 2.2 (macOS 10.12 "Sierra" or newer)  
  https://dotnet.microsoft.com/download/thank-you/dotnet-runtime-2.2.3-macos-x64-installer

### Ubuntu:
* .NET Core 2.2  
  https://dotnet.microsoft.com/download/linux-package-manager/ubuntu16-04/runtime-2.2.3
  
## 下载:
去下载原作者的包(https://github.com/master131/iFakeLocation/releases)。把本项目中~/Resources/index.html替换掉就是中文版啦。

## 运行方法:
### Windows:
双击iFakeLocation.exe.

### Mac OSX
Open the DMG and drag the application to the Desktop or Applications folder. Double-click to run the app.

### Ubuntu
```
chmod +x iFakeLocation
./iFakeLocation
```

## 如何匹配iOS的版本号?

一般情况下，第一次连接，本系统会自动为你下载相应的开发者镜像驱动，如果下载速度太慢，可以手动下载。
If for whatever reason the automatic developer image retrieval doesn't work, you can manually download them to be used in iFakeLocation.
Create a folder called "DeveloperImages" (next to the iFakeLocation executable) and inside that folder make a folder for the iOS version you are running (eg. "12.4", "13.0", etc). Download the matching developer images below and place them in the corresponding folder.

| iOS Version | Developer Images Link |
|-------------|-----------------------|
| 12.3/12.4   |[DeveloperDiskImage.dmg](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/12.3%20(16F148)/DeveloperDiskImage.dmg)<br>[DeveloperDiskImage.dmg.signature](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/12.3%20(16F148)/DeveloperDiskImage.dmg.signature)|
| 13.0        |[DeveloperDiskImage.dmg](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/13.0%20(17A5565b)/DeveloperDiskImage.dmg)<br>[DeveloperDiskImage.dmg.signature](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/13.0%20(17A5565b)/DeveloperDiskImage.dmg.signature)|
| 13.1        |[DeveloperDiskImage.dmg](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/13.1%20(17A844)/DeveloperDiskImage.dmg)<br>[DeveloperDiskImage.dmg.signature](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/13.1%20(17A844)/DeveloperDiskImage.dmg.signature)|
| 13.1.1      |[DeveloperDiskImage.dmg](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/13.1%20(17A853)/DeveloperDiskImage.dmg)<br>[DeveloperDiskImage.dmg.signature](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/13.1%20(17A853)/DeveloperDiskImage.dmg.signature)|
| 13.2        |[DeveloperDiskImage.dmg](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/13.2%20(17B5068e)/DeveloperDiskImage.dmg)<br>[DeveloperDiskImage.dmg.signature](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/13.2%20(17B5068e)/DeveloperDiskImage.dmg.signature)|
| 13.2.2/13.3 |[DeveloperDiskImage.dmg](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/13.2%20(17B102)/DeveloperDiskImage.dmg)<br>[DeveloperDiskImage.dmg.signature](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/raw/master/Developer%20Disk%20Image/13.2%20(17B102)/DeveloperDiskImage.dmg.signature)|

ie.<br>
DeveloperImages\12.4\DeveloperDiskImage.dmg<br>
DeveloperImages\12.4\DeveloperDiskImage.dmg.signature<br>
<br>
Can't find your iOS version? Have a look here, sometimes an older image will work (ie. you can use iOS 13.2.2 image for iOS 13.3):<br>
https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/tree/master/Developer%20Disk%20Image

## 如何使用:
* 连接设备，如果列表中没有列出，请点击“刷新”。

* Enter the desired location (ie. Sydney NSW) in the box and hit "Search" (try to be
  more specific if you are getting strange results).

  You can also manually place a pin on the map by double-clicking anywhere.

* Click "Set Fake Location". If it is the first time doing this the tool
  needs to download some files to enable Developer Mode on your iDevice.

* Confirm your fake location using Apple Maps, Google Maps, etc. To stop the fake location,
  click "Stop Fake Location". If your device is still stuck at the faked location
  turn Location Services off and on in Settings > Privacy.

* Your device will also have a Developer menu now shown in Settings. You can get rid of it 
  by restarting your iDevice.

## Help:
Q: My device doesn't show up on the list?  
A: Ensure that it is plugged in, you have trusted your PC and that the device is visible on iTunes.

## Special Thanks:
* [idevicelocation by JonGabilondoAngulo](https://github.com/JonGabilondoAngulo/idevicelocation)
* [Xcode-iOS-Developer-Disk-Image by xushuduo](https://github.com/xushuduo/Xcode-iOS-Developer-Disk-Image/)
