[//]: # (For GitHub only)
<a href="https://www.buymeacoffee.com/gbraad" target="_blank"><img src="https://img.shields.io/badge/Import%20via%20HA%20Blueprint%20Exchange-18BCF2?logo=homeassistant&logoColor=white" height="30" /></a>  
# Sonoff TX Ultimate Ambient Light
Turns ambient light on if all channels are off & turns ambient light off as soon as one channel is on.  
Ambient light will automatically switch on at specified start time if all channels are off & will automatically switch off at specified end time.  

Version: 1.0  

**Targeted device:** 
 * [Sonoff TX Ultimate (T5) Wall Switch](https://sonoff.tech/product/smart-wall-switches/tx-ultimate/)

**Prerequisites:**
* Sonoff Integration (See [AlexxIT-SonoffLAN](https://github.com/AlexxIT/SonoffLAN))


**Problem:**
* Unable to identify if a switch is on or off when ambient light is on

**Solution:** 
* Only turn on ambient light if all channels are off & turn ambient light off as soon as one channel is on.
* Automatically turn on ambient light at specified start time, only if all channels are off.
* Automatically turn off at specified end time.

**Configuration:**
* Start Time:  
  Time which ambient light will be effective from. e.g. "18:00:00" for 6PM  
  
* End Time:  
  Time which ambient light will turn off. e.g. "6:00:00" for 6AM  

* TX Switch:  
  The Switch which will trigger the automation.
  For multi-channel switches, use a [helper group](https://www.home-assistant.io/integrations/group)

* TX Ambient Light:  
  The ambient light which will turn on or off
  
  
If you like this blueprint or just want to show your support:  
<a href="https://buymeacoffee.com/shaylen" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" height="30" /></a>


Screenshots:  
Without group
With group
