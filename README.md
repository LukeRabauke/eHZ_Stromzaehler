# eHZ_Stromzaehler

This Project is about reading out a German "Stromzähler" provided by EnBW in South Germany eHZ-IW8E2A5L0EK2P using a Hichi TTL IR EHZ Volkszaehler Smartmeter..could also be applied for other eHZ Devices.

Setup:
-ESP8266
-ESP Batteryshield 1.2
-LiPo Battery
-Hichi Lesekopf


Short How To:
-Bring Hardware Parts together, solder Resistor Bridge on ESP Battery Shield
-Flash ESP with Tasmota Generic Setup
-Bring Up Tasmota Setup in WEB UI (Wifi, MQTT)
-Change Script Setting in Tasmota Using consolte.txt file
-Change GPIO Settings to measure Voltage on A0 Pin to "ADC Input"
-Configure the ADC Input like in analog_input.txt to have the Analog Value converted to mV


HAVE FUN
Luke Rabauke