## ESP8266 and ESP32 send email via API example ##

This Arduino sketch implements most simple way to send an email using ForoElectro REST API.


### Configuration ###

In order to use the API you need to get a ForoElectro account (free) at: https://www.foroelectro.net/arduino/

You have to validate your email in order to prevent SPAM abuse.

Then you can copy your ApiKey in this line of the sketch:

char* ApiKey = "YOUR_APIKEY";


You also need to enter your WiFi details in the sketch:

char* ssid = "YOUR_WIFI_SSID";
char *password = "YOUR_WIFI_PASSWORD";



### Compilation ###

You can compile the sketch using Arduino IDE with support for your board.


### Usage ###

When started, sketch connects to your WiFi and then sends an email request to the API (just last command of setup function).

Mail sending is implemented in emailMe() function, and it's so simple that even it only uses server's IP, in order to skip even DNS resolution.


### Hardware ###

No extra hardware is needed, except for power supply.


## Who do I talk to? ##

 * [Naguissa](https://github.com/Naguissa)
 * https://www.foroelectro.net/servicios-de-la-web-f28/envio-de-correos-electronicos-con-una-llamada-http-t408.html
 * https://www.naguissa.com



## Contribute ##

Any code contribution, report or comment are always welcome. Don't hesitate to use GitHub for that.


 * You can sponsor this project using GitHub's Sponsor button: https://github.com/Naguissa/ESP_email_API
 * You can make a donation via PayPal: https://paypal.me/foroelectro


Thanks for your support.


Contributors hall of fame: https://www.foroelectro.net/hall-of-fame-f32/contributors-contribuyentes-t271.html
