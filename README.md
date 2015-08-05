# Project
FLoRa is an Open Source project building platforms and drivers based on Semtech's LoRa 433Mhz technology. LoRa is a Low Power  Wide Area Network technology that allows sensors and IoT devices to communicate up to xxx km using the 433MHz radio spectrum, which is unlicensed (free for the public to use) in most countries. The technology is designed for extremely low power consumption making it ideal for battery and solar powered applications, including but not limited to : high altitude balloons, Unmanned Aerial Vehicles, Agricultural Monitoring, Smart Grids and the list goes on.

The FLoRa project aims to make LoRa technology available for makers, hackers and hobbyists alike at low cost and based on an Open Source Software model. Initial complexity and confusion from interfacing to radio hardware at a low level can be overcome by building a community around a standardized platform that is well documented and supported. Think OpenWRT.

Once the hardware is up and going we have an easy to use API that supports MQTT and AT commands. For folks that are already setup with an IoT framework, MQTT allows for easy interfacing straight in there. For folks that are developing gateways and the like, AT commands means that your PC or dev board will see and communicate with  the FLoRa module in the same way it does with a USB 3G dongle.

### Roadmap - LoRa module for Raspberry Pi, Arduino, Beagle Bone, Edison, OpenWrt
	1. Develop an affordable mini PCIe LoRa module with well documented drivers
	2. Develop shields, hats and headers for the following boards
	3. Create an open source project to support development and interfacing using 

### Whats the problem wit h the LoRa modules available today?
Currently there are low cost embedded modules available that ultilize LoRa technology, however the HAL support is limited at best when compared to the well documented Hardware Abstraction Layers for technologies such as WiFi and Bluetooth. Commercially supported development kits ar eavailable in the market 

### Which Commercial Interests are Active in the LoRa Space?
IBM, Cisco and a handful of European Service providers have or are developing LoRa technologies for commercial use. Development kits are currently available on the market with a price tag to suit, making it challenging to get new IoT products off the ground and into the field.

### Whats the green twist?
Flora is good for the environment. Remote monitoring reduces time and energy expended in managing sytems.

