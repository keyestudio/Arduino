# **Install CP2102 Driver on MAC System**

Connect board we provide to your computer, and open Arduino IDE.

![File:====9.png](./media/542px-%253D%253D%253D%253D9.png)

Click "Tools" to select **Board: Arduino Uno** and **Port: /dev/cu.usbserial-0001**.

![File:====10.png](./media/768px-%253D%253D%253D%253D10.png)

Tap ![image-20230601153931790](media/image-20230601153931790.png) to upload code, if burn successfully, you will view Done uploading.

![File:====11.png](./media/534px-%253D%253D%253D%253D11.png)

Note: If burn unsuccessfully, you need to install driver of CP2102, please continue to follow the instructions as below:

Download the driver of CP2102:[https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers)

1\. Select Mac OSX edition

![File:====12.png](./media/800px-%253D%253D%253D%253D12.png)

2\. Unzip the downloaded package

![====13.png](./media/700px-%253D%253D%253D%253D13.png)

3\. Open folder and double-click SiLabsUSBDriverDisk.dmg file.

![====14.png](./media/700px-%253D%253D%253D%253D14.png)

4\. You will view the following files as follows:

![====15.png](./media/700px-%253D%253D%253D%253D15.png)

5\. Double-click Install CP210x VCP Driver, tick Don’t warn me and tap Open.

![====16.png](./media/700px-%253D%253D%253D%253D16.png)

6\. Tap Continue

![====17.png](./media/700px-%253D%253D%253D%253D17.png)

7\. Tap Continue and Agree

![====18.png](./media/700px-%253D%253D%253D%253D18.png)

8\. Click Continue and input your password

![====19.png](./media/700px-%253D%253D%253D%253D19.png)

![====20.png](./media/700px-%253D%253D%253D%253D20.png)

9\. Select Open Security Preferences

![====21.png](./media/700px-%253D%253D%253D%253D21.png)

10\. Click the lock to unlock security & privacy preference.

![====22.png](./media/700px-%253D%253D%253D%253D22.png)

![====23.png](./media/700px-%253D%253D%253D%253D23.png)

11\. Then click Allow

![====24.png](./media/700px-%253D%253D%253D%253D24.png)

12\. Back to installation page, and wait to install.

![====25.png](./media/700px-%253D%253D%253D%253D25.png)

13\. Successfully installed

![====26.png](./media/700px-%253D%253D%253D%253D26.png)

14\. Then enter ArduinoIDE, click Tools and select Board: Arduino Uno and /dev/cu.SLAB_USBtoUAPT

![====27.png](./media/700px-%253D%253D%253D%253D27.png)

15\. Click![0486-23.png](./media/0486-23.png) to upload code and you will see “Done uploading”.

![====28.png](./media/700px-%253D%253D%253D%253D28.png)



