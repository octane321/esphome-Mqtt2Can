# MQTT to CAN Controller made for IObroker 
**(supports multiple JK-BMS via MQTT and a Shunt with partial override functionality)**


still under development

This is a fork of the very well documented repo of Sleeper85
Please see the original Repo for any questions regarding other topics than multiple BMS and full MQTT support made for IObroker

## File Scructure

**Please note:**

The subfolders and files must be placed in your main esphome folder (where the mqtt-to-can-controller.yaml is.
* Like this:
  
 /mqtt-to-can-controller.yaml

 /common/wifi.yaml

 /common/mqtt.yaml
 
 /common/esp_basics.yaml
 
 /custom/mqtt-to-can-controller/logic.yaml
 
 /custom/mqtt-to-can-controller/sensors_global.yaml
 
 /custom/mqtt-to-can-controller/sensors_jk_bms.yaml
 
 /custom/mqtt-to-can-controller/sensors_shunt.yaml
 
 /custom/mqtt-to-can-controller/combine.yaml

## References

* https://github.com/Sleeper85/esphome-jk-bms-can Big thanks go to @Sleeper85 for time and effort continuing the original Repo as open Source.
* https://www.patreon.com/Uksa007Codedevelopment Thanks to @uksa007 for making the original CAN code.

