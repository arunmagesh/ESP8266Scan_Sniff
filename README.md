# ESP8266Scan_Sniff
This program will Scan for WiFi AP, displays it and starts sniffing it in Wireshark

This combines https://github.com/arunmagesh/esp8266Xscan and https://github.com/spacehuhn/ArduinoPcap

Step:

1. Connect ESP8266 board and install its board file from board manager
2. Install the ArduinoPCAP library and all the supporting libraries in it's GIT( you don't have an option
3. Install Python3 and Pyserial3 and run it as " sudo python3 StartScan_Sniff.py " and reset the board. 


Credits to @spacehuhn for creating this awesome library. 

Note: Bare with the starting garbage value in the terminal. That's basically the ESP8266 boot message. Don't freak-out.
