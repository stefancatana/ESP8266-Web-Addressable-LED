# ESP8266-Web-Addressable-LED
Web interface to control addressable 5V LED strip

In esp8266_webinterface.ino replace WIFI_SSID and WIFI_PASS with your own. You must also change LED_COUNT to the number of LEDs you have on your strip. You may also change LED_PIN as you wish.

Next you have to do some simple wiring like in the picture below
![Screenshot 2021-04-18 213350](https://user-images.githubusercontent.com/50721708/115156738-71cd1d00-a08e-11eb-966d-21e5c9daa4f1.png)

Now connect the ESP to the PC and upload the code. 
After about one minute you can open a browser and go to 192.168.0.124 where you will be granted with a interface to control your LEDs
