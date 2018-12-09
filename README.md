FOR MAKING THIS PROJECT TO RUN ANY ENVIRONMENT THIS STEPS NEEDED TO BE FOLLOWED:
- INSTALL [RASPBIAN OS](https://www.raspberrypi.org/downloads/raspbian/) INTO A [RASPBERRY PI](http://bdspeedytech.com/index.php?route=product/product&product_id=2674&search=RASPBERRY+PI) AND INSTALL [MOSQUTTO](https://www.instructables.com/id/Installing-MQTT-BrokerMosquitto-on-Raspberry-Pi/) ON IT. OPEN A WEB SOCKET AT PORT 1900
- INSTALL ANACONDA FOR PYTHON 3.5 OR GETTER ON YOUR DUMPER SYSTEM. INSTALL PAHO.MQTT AND PYMYSQL LIBARRY IN PYTHON.
- SETUP ANGULAR 6 ENVIRONMENT WITH [NGX-MQTT-CLIENT](https://www.npmjs.com/package/ngx-mqtt-client) AND THE ON TO THE CLIENT ENVIRONMENT. COMPILE THE ANGULAR PROJECT AND RUN IT INTO THE 4200 PORT
- CONFIQURE ANDUINO IDE TO ABLE TO WORK WITH ESP8266 BOARDS. ADD [PUBSUB LIBARRY](https://github.com/knolleary/pubsubclient) INTO THE ARDUINO IDE.
- INTALL XAMPP INTO THE DUMPER SYSTEM FOR UPLOADING DATA INTO MYSQL. DB SCRIPT WILL BE FOUND IN THE PROJECT REPOSITARY. MAKE A DATABASE CALLED [iotProjectV2](https://github.com/extinctCoder/iotProject_2/blob/master/dataDumper/iotprojectv2.sql)

N.B.	USE FIREFOX DEVELOPER EDITION FOR THE ANGULAR PROJECT. IF YOU ARE USING CHROME THERE MAYBE CROSS DOMAIN PERMISSION ARE NEEDED TO BE GIVEN.
	FOR THE IDE CHOICES RECOMENDATIONS ARE PYCHARM PROFESSIONAL EDITION, WEBSTROME PROFESSIONAL EDITION, ARDUINO IDE, CYBERDUCK, CMDER
