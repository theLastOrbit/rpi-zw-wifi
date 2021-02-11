# Simultaneous / Separate AP and Managed Mode Wifi on Raspberry Pi

###### Special thanks to: https://github.com/lukicdarkoo/rpi-wifi


## Usage
```
curl https://raw.githubusercontent.com/md-rubel/rpi-zw-wifi/master/bothAPSTA | bash -s -- -a MyAP myappass -c WifiSSID wifipass

```

```
curl https://raw.githubusercontent.com/md-rubel/rpi-zw-wifi/master/onlyAP | bash -s -- -a MyAP myappass

```

```
curl https://raw.githubusercontent.com/md-rubel/rpi-zw-wifi/master/onlySTA | bash -s -- -c WifiSSID wifipass

```