# DeviceInfo
Easy info about Android device [ ![Download](https://api.bintray.com/packages/eyeem/maven/deviceinfo/images/download.svg) ](https://bintray.com/eyeem/maven/deviceinfo/_latestVersion)

(currently) available info:
- is7inch;
- is10inch;
- isPortrait;
- isLandscape;
- isPhone;
- isTablet;
- isAmazon;
- heightPixels;
- widthPixels;
- statusBarHeight;
- navigationBarHeight;
- diagonalScreenSize;
- displayRealSize;

```Java
// add to your dependencies
compile 'com.eyeem.deviceinfo:library:<latest>'
```

```Java
// get reference to latest info
DeviceInfo di = DeviceInfo.get(context);

// use as needed
if(di.isPortrait) {
   view.getLayoutParams.width = di.widthPixels;
}
```

Pull requests welcome!
