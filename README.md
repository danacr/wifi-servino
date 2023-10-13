# WiFi Servino

Using an [Arduino MKR 1010](https://store.arduino.cc/products/arduino-mkr-wifi-1010) to build a servo controller over wifi.

`arduino_secrets.h` contents:
```c++
#define SECRET_SSID " " //  your network SSID (name) between the " "
#define SECRET_OPTIONAL_PASS " " // your network password between the " "
```

to trigger:
```bash
curl http://192.168.1.88/H
curl http://192.168.1.88/L
```