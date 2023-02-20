# Raspberry Pi Image Configuration
Step-by-step instructions for configuring Raspberry Pi Image for use with the [VPNTV](https://github.com/d3vilh/vpntv) project.

1. Download and install the latest version of Raspberry Pi Imager from the [official website](https://www.raspberrypi.org/software/).

2. Insert SD card into your computer.

3. Open Raspberry Pi Imager and click on the `"CHOOSE OS"` (Step1) button:
   
   <img src="https://github.com/d3vilh/vpntv-hardware/raw/main/Images/Imager-config.0.png" alt="RaspiOS Imager main window" width="600" border="1" />

    1. Select the operating system you want to install. By clicking on the `"Raspberry Pi OS Other"`.
   
    <img src="https://github.com/d3vilh/vpntv-hardware/raw/main/Images/Imager-config.0.1.png" alt="Step1.0" width="600" border="1" />

    2. Then select the `"Raspberry Pi OS Lite (64-bit) with no Desktop env"` version:

    <img src="https://github.com/d3vilh/vpntv-hardware/raw/main/Images/Imager-config.0.2.png" alt="Step1.1" width="600" border="1" />

    > **Note**: For the Raspberry Pi Zero W1 you must to go with the **RaspiOS Lite (32-bit) with no Desktop env** version, as shown on the screenshot above. 

4. Select the SD card you want to install the operating system on by click to `"CHOOSE STORAGE"` (Step2) button:

   <img src="https://github.com/d3vilh/vpntv-hardware/raw/main/Images/Imager-config.0.png" alt="RaspiOS Imager main window" width="600" border="1" />

5. Click on the `"GEARBOX"` (Step3) icon to open the "Advanced Options" window and configure the following options:
   1. Set the hostname of your Raspberry Pi. For example, `vpntv`:
    <img src="https://github.com/d3vilh/vpntv-hardware/raw/main/Images/Imager-config.1.png" alt="Step3.0" width="600" border="1" /> 
   2. Set the uniq password for the `vpntv` user. For example, `Uniqu3_pa$Sword!:)` and set the SSID of your local WiFi network which you are using for Internet conncetion:
    <img src="https://github.com/d3vilh/vpntv-hardware/raw/main/Images/Imager-config.2.png" alt="Step3.1" width="600" border="1" />
   3. Set desired TimeZone and Keyboard layout:  
    <img src="https://github.com/d3vilh/vpntv-hardware/raw/main/Images/Imager-config.3.png" alt="Step3.2" width="600" border="1" />

6. Click on the `"WRITE"` (Step4!) button to start SD-CARD formatting and OS installation.:
   <img src="https://github.com/d3vilh/vpntv-hardware/raw/main/Images/Imager-config.0.png" alt="RaspiOS Imager main window" width="600" border="1" />

7. When verification process will be completed you will be prompted to remove the SD card from your computer and insert it into your Raspberry Pi. 

8. Plug your Raspberry Pi to the power supply and wait for the first boot, it can take up to the 5 minutes, depends on board you use.

9. Connect to your Raspberry Pi with ssh client, using the user `vpntv` and password you setup on the point 5.1:
   ```bash
   ssh vpntv@<IP ADDRESS of your new Pi>
   ```
10. Continue with [VPNTV software installation steps](https://github.com/d3vilh/vpntv).