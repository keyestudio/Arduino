# **UNO Development Board for Mac**

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

![9a473649d5e8d5920ebda8a0624f1fa9](./media/9a473649d5e8d5920ebda8a0624f1fa9.png)

Choose the correct COM port.

If there are so many ports that you have no idea which is the correct one, you may unplug the board to check which one disappears. If there is no COM port, please check whether the driver is installed.

In “Tools”, click “Port” to select “/dev/cu.usbderial-0001”.

![](./media/1721f18ce120baa9a09440d9887c5cff-1685526089268-109.png)

If your board is successfully connected, it will show on the interface. 

![](./media/11111111-1685530379800-113.png)

Click ![image-20230531164208065](./media/image-20230531164208065.png)to compile the code. If it succeeds, the following two show up:

![](./media/848beee386ba83971f66615b76e66629.png)

Click ![image-20230601084422847](./media/image-20230601084422847.png)and set baud rate to 9600, and “Hello Keyestudio!” are being printed!

![](./media/421d25a177740e6f6390035b16b256f6-1685581181278-12.png)

1. “Toggle Autoscroll”: To set whether to follow the print.
2. “Toggle Timestamp”: To set whether to display printing time.
3. “Clear Output”: To clear the output data.
4. Serial Input
5. Serial port sending format
6. Baud rate: To set the baud rate.
7. Printing box.

This is the end of how to upload code!

Now please import libraries for IDE, otherwise an error will occur. 



