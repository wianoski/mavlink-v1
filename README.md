# mavlink V1

Fixed :Graph, GUI Console, Map

Added :All graph from data, Simple message for mavlink, Graph module 

Delete Map function instead calling another session, 

This mavlink using mavproxy for autonomous, and for the next i'll make a web based gui

How it work :

if you using usb connection then use :

```
mavproxy.py --master com14  --out 127.0.0.1:14550 --out 127.0.0.1:14551 --console
```

calling map (tricky way) : 
```
mavproxy.py --master 127.0.0.1:14550 --map
```

but when you use telemetry connection, then use : 
```
mavproxy.py --master com14 {baudrate} --out 127.0.0.1:14550 --out 127.0.0.1:14551 --console
```

