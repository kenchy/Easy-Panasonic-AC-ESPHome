# Easy-Panasonic-AC-ESPHome
Panasonic AC (with WIFI) comes with an app (Comfort Cloud) which is barely adequate. People have used (abused) this app to create things like https://github.com/sockless-coding/panasonic_cc which gives a Home Assistant interface. Periodically Panasonic change something and the integration breaks. It's not entirey clear if this is to stop the integration or just coincidence, but when you are trying to heat your house in the winter, it's annoying and cold.

Some clever chap here https://github.com/DomiStyle/esphome-panasonic-ac/tree/master has extended the esphome system so it can interface with the Panasonic AC units directly. Either via a CN-CNT port or CN-WLAN. This makes it off line and theoretically unbreakable depending on the reliability of the ESP32.

My aim is to give people a relatively easy to understand list of components that should work with no/minimal soldering and how to get the components.

So far I have one no solder board working and plugged in to the CN-CNT port based on https://github.com/DomiStyle/esphome-panasonic-ac/issues/111 and several failed attempts, and a burnt out ESP8266.


