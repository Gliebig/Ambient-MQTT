# Ambient-MQTT
 This sketch took the initial analysis started by contributors below and was enhanced to be interfaced to send the data
 to an MQTT broker. In my case, this will be using Home Assistant using the HASSIO platform
 Modified by Greg Liebig on 2/3/18
 Updated 2/6/18 with a scan counter to count the number of scans a sensor had during the processing loop. Will only publish
 MQTT packets with a scan value >0. 
