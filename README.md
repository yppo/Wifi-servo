# Wifi-servo
Control a servo via wifi. 

# Hardwar
 * MakerHawk D1 Mini NodeMcu 4M Bytes Lua WIFI Development Board Base on ESP8266 ESP-12F N Compatible NodeMcu Arduino ([Amazon](https://www.amazon.co.uk/MakerHawk-NodeMcu-Development-ESP8266-Compatible/dp/B071S8MWTY))
  * Servo
  
## How to use MakerHawk D1 Mini NodeMcu
### Setup:
* Download the Arduino IDE from the [arduino.cc](https://www.arduino.cc/en/Main/Software).
* I found an OSX driver for the board at github.com on "adrianmihalko" 's page. You will want the files under the ch340g-ch34g-ch34x-mac-os-x-driver
repository.
* Once both of these are installed open up the Arduino IDE
* Go into the preferences and add the url as stated in the product description
above (sorry can't post the url here) * In the "Board Manager" search for and install the latest version of the
"esp8266" generic module
* Select the new "Port" added by the driver: (mine was
"/dev/cu.wchusbserial14120") * Set the "Reset Method" to: nodemcu
* All done!
