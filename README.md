# ISM43362 WiFi driver for mbed-os
The mbed OS driver for the ISM43362 WiFi module

## Currently supported platforms
ISM43362 module is soldered on the following platforms from STMicroelectronics
* DISCO_L475VG_IOT01A
* DISCO_F413ZH

## Configuration

Correct pins have already been configured for both supported platforms.

Here is configured pins:

- MBED_CONF_ISM43362_WIFI_MISO      : spi-miso pin for the ism43362 connection
- MBED_CONF_ISM43362_WIFI__MOSI     : spi-mosi pin for the ism43362 connection
- MBED_CONF_ISM43362_WIFI_SPI_SCLK  : spi-clock pin for the ism43362 connection
- MBED_CONF_ISM43362_WIFI_SPI_NSS   : spi-nss pin for the ism43362 connection
- MBED_CONF_ISM43362_WIFI_RESET     : Reset pin for the ism43362 wifi module
- MBED_CONF_ISM43362_WIFI_DATAREADY : Data Ready pin for the ism43362 wifi module
- MBED_CONF_ISM43362_WIFI_WAKEUP    : Wakeup pin for the ism43362 wifi module


## Firmware version
This driver supports ISM43362-M3G-L44-SPI,C3.5.2.3.BETA9 and C3.5.2.2 firmware version

## wifi module FW update
For more information about the wifi FW version, refer to the detailed procedure in
http://www.st.com/content/st_com/en/products/embedded-software/mcus-embedded-software/stm32-embedded-software/stm32cube-embedded-software-expansion/x-cube-azure.html
