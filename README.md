iOS Face Recognization Module for [Titanium](https://github.com/appcelerator/titanium_mobile)
------------

![Preview](https://raw.github.com/farwayer/TiFaceRecognizer/master/documentation/preview.png)

Сapabilities
------------

All supported by [CIDetector](https://developer.apple.com/library/ios/documentation/CoreImage/Reference/CIDetector_Ref/Reference/Reference.html).
Async recognize.

Install
-------

1. Run `build.py` which creates your distribution
2. cd to `/Library/Application Support/Titanium`
3. copy this zip file into the folder of your Titanium SDK

Register in application
-----------------------

Register module in your application by editing `tiapp.xml`:
```xml
    <modules>
	    <module version="1.0">by.farwayer.facerecognizer</module>
    </modules>
```

Usage
-----
Look examples in [app.js](https://github.com/farwayer/TiFaceRecognizer/blob/master/example/app.js)
