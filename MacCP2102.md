# **Install CP2102 Driver on MAC System**

Connect board we provide to your computer, and open Arduino IDE.

![File:====9.png](./media/40A968D312A8B080E52C4559201F498A.png)

Click "Tools" to select **Board: Arduino Uno** and **Port: /dev/cu.usbserial-0001**.

![File:====10.png](./media/3123378638D9C83554A2C90BFA436BCF.png)

Tap ![image-20230601153931790](media/image-20230601153931790.png) to upload code, if burn successfully, you will view Done uploading.

![File:====11.png](./media/E97244571B69D21FF31DE3B879B8B0E5.png)

Note: If burn unsuccessfully, you need to install driver of CP2102, please continue to follow the instructions as below:

Download the driver of CP2102:[https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers)

1\. Select Mac OSX edition

![File:====12.png](./media/6E53A3DACDEC57D5EE0B15B48D771A5B.png)

2\. Unzip the downloaded package

![====13.png](./media/8DCED2768D5F86D3D0C3F6076D87A9A8.png)

3\. Open folder and double-click SiLabsUSBDriverDisk.dmg file.

![====14.png](./media/61AE3E706A1C4AFA7948D5FB2E797A6D.png)

4\. You will view the following files as follows:

![====15.png](./media/3FFD0525E16492EDE92BDB8C84198DB9.png)

5\. Double-click Install CP210x VCP Driver, tick Don’t warn me and tap Open.

![====16.png](./media/14F6EBB088E654ABC2F0149645E34ED1.png)

6\. Tap Continue

![====17.png](./media/A243872CDBB520E4D298C006E001FFF5.png)

7\. Tap Continue and Agree

![====18.png](./media/AE367C1894DF6745E46BBDFC460C1F99.png)

8\. Click Continue and input your password

![====19.png](./media/27B7214283D7F76ABA3557DD629BD965.png)

![====20.png](./media/29BBCA3360D806164717733460574356.png)

9\. Select Open Security Preferences

![====21.png](./media/CA6BC6E536202F07A53C09201A0996FF.png)

10\. Click the lock to unlock security & privacy preference.

![====22.png](./media/379CAA1889F4A45614B27C9B2B934869.png)

![====23.png](./media/88A1B169A192EE6C49E95947D6287FC2.png)

11\. Then click Allow

![====24.png](./media/19E43624EFDE1B223800201C944D25E9.png)

12\. Back to installation page, and wait to install.

![====25.png](./media/BB0E17AFD8BAD8B8013F19D7A9DA0FD9.png)

13\. Successfully installed

![====26.png](./media/3BD5BB3752ABF97E9BAB6BF950A75BED.png)

14\. Then enter ArduinoIDE, click Tools and select Board: Arduino Uno and /dev/cu.SLAB_USBtoUAPT

![====27.png](./media/73AED810D216D7DA3A3CE9CC0E4DBA4A.png)

15\. Click![0486-23.png](./media/0486-23.png) to upload code and you will see “Done uploading”.

![====28.png](./media/D918E2E31A9632F8B272A16595C46A83.png)


