#Arduino Zigduino Package 
Configuration of Zigduino boards that can be loaded by the Arduino board manager. 

Containts :

	- JSON file required by Arduino IDE to install the package
 
	- Zigduino package


#Installation 



## 1 - Download the lastest Arduino IDE

You need a Arduino IDE version 1.6.10 or later, download link : [here](https://www.arduino.cc/en/Main/Software)



## 2 - Setting your Arduino IDE 

Open your Arduino IDE, click on **File > Preferences**, and copy below url to *Additional Boards Manager URLs*

```
https://raw.githubusercontent.com/icube-inetlab/arduino-zigduino-package/master/package/package_zigduino_index.json
```

![Add URL](img/select_json_file.png)


## 3 - Board Manager 

Click on **Tools > Board > Board Manager**

![Board Manager](img/board.png)


## 4 - Select and install Zigduino AVR Board 

![Add board](img/add_board.png)


## 5 - Use a Zigduino Board 

Click on **Tools > Board**, *zigduino_r1* and *zigduino_r2* are available now.

![Select board](img/select_board.png)


#Usage 

When you need to modify the package, after create the zip file use this command


	shasum -a 256 zigduino-avr_1.0.0.zip


Copy en replace the SHA-256 in the JSON file.

Don't forget to ckeck and modify the zip size in the JSON file   






package created from :  [here](https://github.com/logos-electromechanical/Zigduino-1.0)
