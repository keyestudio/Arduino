# **MAC Arduino IDE ESP32 Development Board**

Typically, we cannot find ESP32 board from “Board” in “Tools”. Because we have not install this board on Arduino IDE yet.

![1234](./media/1234.png)

Here are the procedures of ESP32 board installation:

Open Arduino IDE.

Click “**Arduino IDE** ——>**Preferences**”. 

Copy the link of ESP32 board (https://espressif.github.io/arduino-esp32/package_esp32_index.json) to Additional boards manager URLs, and tap OK.

![](./media/new(20)-1682391468738-45.png)

Click the icon of "Board Manager" to check for boards.

![](./media/image-20230601082620991.png)

In the search bar, type in ESP32 and search to install the latest version. Then you just need to wait a few minutes for the installation to complete. 

**During installing, please ensure the stability of network. If it fails, please operate last step again to re-install.**

![](./media/d02ff28111903cff5e03cd7aaa354bfa.png)

It is successfully installed! 

![image-20230601082915468](./media/image-20230601082915468.png)

After installation, select the right board model.

![](./media/4d5122d546affac2bcb4a12e7d9ff86f.png)

Choose the correct COM port.

If there are so many ports that you have no idea which is the correct one, you may unplug the board to check which one disappears. If there is no COM port, please check whether the driver is installed.

In “Tools”, click “Port” to select “/dev/cu.usbderial-0001”.

![1ce7f81a12a94c95c61eecb07caa7d93](./media/1ce7f81a12a94c95c61eecb07caa7d93.png)

If your board is successfully connected, it will show on the interface. 

Now you can try to upload code. An examples code is provided here: it will print “Hello Keyestudio!” per second.

![image-20230601083918951](./media/image-20230601083918951.png)

Copy and paste the following code to Arduino IDE: 

```c
/*
  keyestudio 
  Print “Hello Keyestudio!”
  http://www.keyestudio.com
*/
void setup() {  
    // put your setup code here, to run once:
    Serial.begin(9600);  //Set the serial port baud rate to 9600
}

void loop() {  
    // put your main code here, to run repeatedly:
    Serial.println("Hello Keyestudio!");  //Serial port printing
 	delay(1000);  //Delay of 1 second
}
```

Click ![image-20230531164208065](./media/image-20230531164208065.png) to compile the code. If it succeeds, the following two show up:

![](./media/image-20230601084247459.png)

While uploading, if it outputs “————……..————……..”, please press and hold “**Boot**” button on your board. However, this only works for Keyestudio ESP32 development board (Keyestudio Plus ESP32 is excluded).

Click ![image-20230601084356690](./media/image-20230601084356690.png) and set baud rate to 9600, and “Hello Keyestudio!” are being printed!

![](./media/421d25a177740e6f6390035b16b256f6.png)

1. “Toggle Autoscroll”: To set whether to follow the print.
2. “Toggle Timestamp”: To set whether to display printing time.
3. “Clear Output”: To clear the output data.
4. Serial Input
5. Serial port sending format
6. Baud rate: To set the baud rate.
7. Printing box.

This is the end of how to upload code!

Now please import libraries for IDE, otherwise an error will occur. 

