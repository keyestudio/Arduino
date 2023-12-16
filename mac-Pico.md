# **Pico Development Board for Mac**

Typically, we cannot find Pico board from “Board” in “Tools”. Because we have not install this board on Arduino IDE yet.

![1234](./media/1234-1698713479663-1.png)

Here are the procedures of Pico board installation.

Open Arduino IDE. Then click Board Manager![image-20230601091859259](./media/image-20230601091859259.png):

![](./media/image-20230601095500439.png)

In the search bar, type in **Pico** and search to install **Arduino Mbed OS RP2040 Boards**. 

![](./media/image-20230601095706652.png)

When “**Install**” becomes “**REMOVE**”,and a prompt pops up, installation is successfully complete. 

![](./media/image-20230601100536701.png)

Now you can find pico board in “Board”!

![](./media/8ee289066995bdd5e69454816de1dafb.png)

The following step is extremely essential: Upload Pico firmware that is compatible with arduino. Because arduino IDE cannot burn programs on Pico board if there is no such firmware. 

For how, lease refer to the configuration below: 

（1）Disconnect Raspberry Pi Pico to computer. Press and hold the white button(BOOTSEL) on Raspberry Pi Pico until the board is linked to PC. (Always remember to hold the button until connection is finished, or else firware fails to be downloaded. )

![img](./media/wps4-1685583374018-14.jpg) 

（2）Open Arduino IDE, click **File** → **Examples** → **01.Basics** → **Blink**.

![](./media/image-20230601093948655.png) 

（3）Click **Tools** → **Board** → **Arduino Mbed OS RP2040 Boards** → **Raspberry Pi Pico**.

![](./media/image-20230601102128751.png) 

（4）Upload Sketch **Blink** to Pico and click ![image-20230601094348371](./media/image-20230601094348371.png)to compile the code. **Done uploading** will be displayed after successful uploading. 

![](./media/image-20230601102203136.png) 

The indicator on Pico board will blink per second. 

![image-20230601094438678](./media/image-20230601094438678.png)

Click **Tools** → **Port** → **/dev/cu.sudmodem14101(Raspberry Pi Pico)**. 

![](./media/image-20230601102314563.png)



**NOTE**

**A.** **Uploading Sketch via Arduino to Pico for the first time, no port selection required. Yet, every time after that, you need to check whether the port is selected; otherwise the download may fail.**

**B.** **Sometimes, Pico board may not work due to firmware missing. At this moment, please upload firmware again.**



