# **UNO Development Board for Windows****

Upload code: An examples code is provided here: it will print “Hello Keyestudio!” per second.

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

![](./media/image-20230531163632939.png)

Click “Tools”——>“Board”——> Arduino AVR Boards, and here we choose Arduino Uno as our development board. 

![](./media/123456-1685520938684-103.png)

Choose the correct COM port.

If there are so many ports that you have no idea which is the correct one, you may unplug the board to check which one disappears. If there is no COM port, please check whether the driver is installed.

![wps11](./media/wps11.jpg)

In our demostration, the port is COM3, so we click “Tools”to choose“COM3” in “Port”.

![456789](./media/456789.png)

If your board is successfully connected, it will show on the interface. 

![image-20230531164139295](./media/image-20230531164139295.png)

Click ![image-20230531164208065](./media/image-20230531164208065.png)to compile the code. If it succeeds, the following two show up:

![image-20230531164344269](./media/image-20230531164344269.png)

Click ![image-20230601084450267](./media/image-20230601084450267.png)and set baud rate to 9600, and “Hello Keyestudio!” are being printed!

![20230531164555](./media/20230531164555.png)

1. “Toggle Autoscroll”: To set whether to follow the print.
2. “Toggle Timestamp”: To set whether to display printing time.
3. “Clear Output”: To clear the output data.
4. Serial Input
5. Serial port sending format
6. Baud rate: To set the baud rate.
7. Printing box.

This is the end of how to upload code!

Now please import libraries for IDE, otherwise an error will occur. 





