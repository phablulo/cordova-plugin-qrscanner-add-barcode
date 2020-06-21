## QR Scanner v3.0.1 Add Barcode Mod
URL: https://github.com/bitpay/cordova-plugin-qrscanner/issues/132


## Function
Add QR Scanner to support EAN-13, CODE-128, CODE-39.

Tested with: cordova-android: 8.1.0, cordova-ios: 5.1.1


## How To Use
1) Place all files under "hooks/qrscanner_add_barcode/".

2) Add below in "config.xml":
```xml
<platform name="android">
  <hook src="hooks/qrscanner_add_barcode/301_android.js" type="after_prepare" ></hook>
</platform>
<platform name="ios">
  <hook src="hooks/qrscanner_add_barcode/301_ios.js" type="after_prepare" ></hook>
</platform>
<preference name="UseSwiftLanguageVersion" value="5" ></preference>
```
## TODO

- add methods to change camera bounds on iOS.
