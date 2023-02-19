# vpntv-hardware
Hardware Options for vpntv project

- [**Raspberry Pi Zero W**](https://www.raspberrypi.org/products/raspberry-pi-zero-w/) or [**Raspberry Pi Zero W2**](https://www.raspberrypi.org/products/raspberry-pi-zero-w-2/) board, all with 512Mb RAM minimum.
- [**Raspberry Pi 4**](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/), [**Raspberry Pi CM4**](https://www.raspberrypi.com/products/compute-module-4/?variant=raspberry-pi-cm4001000) **and** [**CM4 I/O Board**](https://www.raspberrypi.com/products/compute-module-4-io-board/) or [**Raspberry Pi 3**](https://www.raspberrypi.com/products/raspberry-pi-3-model-b-plus/) board, all with 2Gb RAM minimum.
- [**Raspberry Pi Imager**](https://www.raspberrypi.com/software/) to simplify installation of Raspberry Pi OS Lite (32-bit or 64-bit).
- [**Raspios Lite (32-bit)**](https://downloads.raspberrypi.org/raspios_lite_armhf/images/) or [**Raspios Lite (64-bit)**](https://downloads.raspberrypi.org/raspios_lite_arm64/images/) however 32-bit images is recommended for setup on Raspberry Pi Zero boards.
- **16Gb SD Card**
   > You can run it on CM4 board with 4Gb eMMC EEPROM chip as well.
- **USB WiFi Adapter** (optional). Be sure your adapter supports [AP Mode](https://elinux.org/RPi_USB_Wi-Fi_Adapters) in RaspiOS.
   > **Note**: You can use adapters compatible with builtin vpntv driver, for this you have to set `wifi_mod_enable: true ` in `config.yml` before running installation playbook.
   <details>
     <summary>
       List of WiFi adapters supported by vpntv buildin 8188eus driver.
     </summary>

  * [Realtek RTL8188EUS](https://www.realtek.com/en/products/communications-network-ics/item/rtl8188eus) Wireless LAN 802.11n USB 2.0 Network Adapter. [Aliexpress link](https://a.aliexpress.com/_Ew27JPn)
  * [Realtek RTL8188ETV](https://www.realtek.com/en/products/communications-network-ics/item/rtl8188etv) Wireless LAN 802.11n USB 2.0 Network Adapter. [Aliexpress link](https://a.aliexpress.com/_EGxet6d)
  * TP-Link TL-WN722N V2/V3 150Mbps High Gain Wireless USB Adapter
  * TP-Link TL-WN727N V5.20 150Mbps Wireless N USB Adapter
  * TP-Link TL-WN725N V3 150Mbps Wireless N Nano USB Adapter
  * EDIMAX EW-7811Un V2 N150 Wi-Fi 4 Nano USB Adapter
  * ASUS USB-N10 Nano B1 USB Adapter Wireless-N
  * D-Link DWA-125 Wireless N 150 USB Adapter(rev.D)
  * D-Link DWA-123 Wireless N 150 USB Adapter(rev.D)
  * D-Link GO-USB-N150 Wireless N 150 Easy USB Adapter(rev.B)
  * D-Link DWA-121 Wireless N 150 USB Adapter(rev.B)
  * Realtek RTL8188EU Wireless LAN 802.11n USB 2.0 Network Adapter
  * 802.11bgn Mini Wireless LAN USB2.0 Adapter
  * ELECOM WDC-150SU2M Wireless Adapter
  * Sitecom WLA-1100 V2 Wi-Fi USB adapter N150
  * MERCUSYS MW150US V2 N150 Wireless Nano USB Adapter
  * Rosewill RNX-N150NUB N150 Wireless Nano USB Adapter
</details>

- **USB Ethernet Adapter** (for Raspberry Pi Zero W boards only)

   <details>
     <summary>
       Supported (and tested) Raspberry Pi Zero W USB and Ethernet hats.
     </summary>
  
  * [WaveShare ETH/USB HUB](https://www.waveshare.com/product/raspberry-pi/hats/interface-power/eth-usb-hub-hat-b.htm) HAT for RPi Zero. [Aliexpress link](https://a.aliexpress.com/_EJGKaqH)
  * [Elecrow USB Hub & PowerManager](https://www.elecrow.com/usb-hub-powermanager-for-rpi-zero-v1-0.html) for RPi Zero V1.0. [Aliexpress link](https://a.aliexpress.com/_Exj5Rvf)
</details>
