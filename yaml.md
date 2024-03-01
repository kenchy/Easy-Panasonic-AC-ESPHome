These are my first devices using ESPhome so I've been learning as I go. I saw some people using include files for the yaml config, so I did that. I've got a network yaml with all of the common elements, like ssid, api key etc and a per AC file that contains all the AC options. BTW I've got 6 split AC units so this is why I genericized it, if you only have one, it's not so important.

This is an example of the network yaml:

https://github.com/kenchy/Easy-Panasonic-AC-ESPHome/blob/main/network_pac_common.yaml

You'll need to populate it with all of your values.


The AC yam ls here:

https://github.com/kenchy/Easy-Panasonic-AC-ESPHome/blob/main/generic_pac.yaml

This one just needs the name of the ac unit near the top, but you'll probably want to call it something relevant.

Just put them in the same directory and run "esphome run generic_pac.yaml" and it should build. 
