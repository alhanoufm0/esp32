# esp32

ESP32 Web Server:- 



1- Make sure that your ESP32 is add-on in Arduino IDE, by clicking on files and then go to preferences.

2- In board manager write this url https://dl.espressif.com/dl/package_esp32_index.json (this is a board support package).

3- Now, install library of ESP32 in Arduino IDE, go to tools>>boards and choose board manager.

4- then, a window will appear and in search line you should write:ESP32, click on the option of esp32 and install it.

5- to select the COM port, go to tools and click on port. Select a port to which your board is connected.

6- after that you should write the code, but first you should include wifi library like this:

#include <WiFi.h> 


7- then, you define if somthing like LED is connecting to your esp32 ,so you can control it using your web server.

8- write your code to control your esp32 and don't forget to include html to make the web page

,and a little of css to make your web page neat :) 

9- last but not least, Open the Serial Monitor and you will see some important information like

the URL of the web server 'in fact, it is the IP Address of your ESP32' 

and the progress of Wi-Fi Connection. 


10- finally, open any web browser and the URL (IP Address of your esp32),then you will see your web page

that hosted by the ESP32 Web Server. 


Note: the serial monitor will show you some information about each client connect to the server.
