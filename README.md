# mavlink V1

Fixed :Graph, GUI Console, Map, Toolbar

Added : -

Issues :

``` 
MAVcesium : there's an error at configparser
Magical UI : objects still cant call self paramaters
```

This mavlink using mavproxy for autonomous, and for the next i'll make a web based gui

How it work :

if you using usb connection then use :

```
mavproxy.py --master COM  --out 127.0.0.1:14550 --out 127.0.0.1:14551 --console
```

calling map (this methode using mavproxy that installed before at http://firmware.ardupilot.org/Tools/MAVProxy/) : 
```
mavproxy.py --master 127.0.0.1:14550 --map
```

but when you use telemetry connection, then use : 
```
mavproxy.py --master COM {baudrate} --out 127.0.0.1:14550 --out 127.0.0.1:14551 --console
```

Documentation 

[![Watch the video](https://raw.github.com/GabLeRoux/WebMole/master/ressources/WebMole_Youtube_Video.png)](https://drive.google.com/file/d/1ua-sTieogB6g8PWhwYlY0JLnSj_RUb1Z/preview)

