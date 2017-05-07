# headlessWifi

$ sudo nano /etc/network/interfaces and write:

```
# add this at the end
auto wlan0
iface wlan0 inet dhcp 
wpa-ssid NETWORK_NAME
wpa-psk  PASSWORD
```

$ reboot
