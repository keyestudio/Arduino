#  **Install CH340 Driver on Windows System**

Download: [https://fs.keyestudio.com/CH340-WINDOWS](https://fs.keyestudio.com/CH340-WINDOWS)

Windows 10 (and later systems) boasts their own drivers, so there is no need to install additional drivers.

Connect the control board to your computer.

Click Computer-- Properties -- Device Manager, as shown below. This indicates a successful connection, so the installation of driver is not required. 

![](./media/112.png)

If the following situation occurs, you need to manually install the driver.

![new(14)](./media/new(14).png)

Click ![image-20230531114825326](./media/image-20230531114825326.png)to select “Update driver”. And then the driver will start to install. 

![](./media/new(15).png)

Tap "Browse my computer for drivers".

![new(16)](./media/new(16).png)

Find the file **usb_ch341_3.1.2009.06** or **cp210x** you have downloaded, and click "Next".

![new(17)](./media/new(17).png)

After finishing installing, click "Close" and the serial port number will show up. 

![new(18)](./media/new(18).png)

The driver is successfully installed!

Click Computer-- Properties -- Device Manager to check: 

![](./media/112.png)