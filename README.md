Car_Tracker_V2
==============
GPS Tracker Built Using:

- Uno
- Official Arduino GSM Shield
- Adafruit Ultimate GPS


Basic setup:

- Arduino wake every hour
- Attempt GPS fix for 2 minutes
-- If fix send SMS to twilio number then sleep
-- If no fix go back to sleep
- Repeat


Will be attempting to send Lat/Lon data by sms to twilio which will then go in to Node-Red and through MQTT to MQTTitude.

Work in progress, will show official release when ready with release tag.

@Hardware_Hacks <- Contact me on twitter for further info or support.

http://c-mobberley.com/wordpress <- For all Raspberry Pi Goodness.
