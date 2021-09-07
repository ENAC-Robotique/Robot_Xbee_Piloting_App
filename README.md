# Robot_Xbee_Piloting_App

A flutter app to control a robot using USB and Xbee.


to build for android :
    flutter build apk --split-per-abi

apk already built : 
    app-armeabi-v7a-release.apk
    in build>output>flutter-apk


to modify joystick speed values :
    lib, joystickMode :
    modify line 76/77 - _consSpeed = getSpeed(degrees, distance) * 2000;