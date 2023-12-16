# **Pico Development Board for Windows**

Typically, we cannot find Pico board from “Board” in “Tools”. Because we have not install this board on Arduino IDE yet.

![1234](./media/1234-1698713471727-1.png)

Here are the procedures of Pico board installation.

Open Arduino IDE. Then click Board Manager![image-20230601091859259](./media/image-20230601091859259.png):

![image-20230601091835770](./media/image-20230601091835770.png)

In the search bar, type in **Pico** and search to install **Arduino Mbed OS RP2040 Boards**. 

![image-20230601092113791](./media/image-20230601092113791.png)

If there is a security interface, please click “**Install**” to just install the driver of Pico development board. 

![image-20230601093206151](./media/image-20230601093206151.png)

When “**Install**” becomes “**REMOVE**”,and a prompt pops up, installation is successfully complete. 

![image-20230601092226121](./media/image-20230601092226121.png)

Now you can find pico board in “Board”!

![image-20230601093011251](./media/image-20230601093011251.png)

The following step is extremely essential: Upload Pico firmware that is compatible with arduino. Because arduino IDE cannot burn programs on Pico board if there is no such firmware. 

For how, lease refer to the configuration below: 

（1）Disconnect Raspberry Pi Pico to computer. Press and hold the white button(BOOTSEL) on Raspberry Pi Pico until the board is linked to PC. (Always remember to hold the button until connection is finished, or else firware fails to be downloaded. )

![img](./media/wps4-1685583374018-14.jpg) 

（2）Open Arduino IDE，Click **File** → **Examples** → **01.Basics** → **Blink**.

![](./media/image-20230601093948655.png) 

（3）Click **Tools** → **Board** → **Arduino Mbed OS RP2040 Boards** → **Raspberry Pi Pico**.

![](./media/image-20230601094149905.png) 

（4）Upload Sketch **Blink** to Pico and click ![image-20230601094348371](./media/image-20230601094348371.png)to compile the code. **Done uploading** will be displayed after successful uploading. 

![](./media/image-20230601094317918.png) 

The indicator on Pico board will blink per second. 

![image-20230601094438678](./media/image-20230601094438678.png)

Click **Tools** → **Port** → **COMx(Raspberry Pi Pico)**.

In COMx, X varies from computers. So please select the correct COM port. In our demostration, the port is COM25.

![image-20230601094722643](./media/image-20230601094722643.png)

**NOTE**

**A.** **Uploading Sketch via Arduino to Pico for the first time, no port selection required. Yet, every time after that, you need to check whether the port is selected; otherwise the download may fail.**

**B.** **Sometimes, Pico board may not work due to firmware missing. At this moment, please upload firmware again.**



