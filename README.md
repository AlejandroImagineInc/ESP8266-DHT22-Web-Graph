# ESP8266-DHT22-Web-Graph

Pagina con los archivos download
https://randomnerdtutorials.com/esp32-esp8266-plot-chart-web-server/

## Install ESP8266 Filesystem Uploader in Arduino IDE
https://gndtovcc.home.blog/2020/04/22/install-esp8266-filesystem-uploader-in-arduino-ide-2/
https://gndtovcc.home.blog/2020/04/22/install-esp32-filesystem-uploader-in-arduino-ide/

![image](https://user-images.githubusercontent.com/64314988/114287072-76fced00-9a3a-11eb-8622-9a4eef01ee2f.png)

Uploading Files using the Filesystem Uploader
To upload files to the ESP8266 filesystem follow the next instructions.

1) Create an Arduino sketch and save it. For demonstration purposes, you can save an empty sketch.

2) Then, open the sketch folder. You can go to Sketch > Show Sketch Folder. The folder where your sketch is saved should open.

3) Inside that folder, create a new folder called data.

4)  Inside the data folder is where you should put the files you want to be saved into the ESP8266 filesystem. As an example, create a .txt file with some text called test_example.

5) In the Arduino IDE, in the Tools menu, select the desired SPIFFS size (this will depend on the size of your files)

6) Then, to upload the files, in the Arduino IDE, you just need to go to Tools > ESP8266 Sketch Data Upload.


