**Brickz Bluetooth Infrared Blaster / Transmitter by Irdroid**

**Introduction** 

Brickz is a Open Source Platform Independent Bluetooth Infrared Transmitter / Blaster that supports GNU Linux, MS Windows MAC OS X and Android. Brickz allows you to transmit Pronto HEX Infrared codes via its built-in infrared LEDs or via a IR extender cable that connect to brickz via a 3.5mm Mono Audio jack. The unit is capable of connecting to the host PC via USB as well as Bluetooth. It shows up as a bluetooth serial port, when that interface option is used, or as a USB Serial Device if the USB Interface connection is used.(https://irdroid.eu/product/brickz/)
![Brickz](https://raw.githubusercontent.com/Irdroid/Brickz/main/Documents/Photos/Brickz_with_ir_extender_scaled.png)

**Features:**
- Bluetooth communication with the HOST SYSTEM / MCU
- USB Connection with the host System
- Built-in high power infrared leds
- Optional infrared transmitter extender
- Infrared operates at 940nm wavelength

**Example Application:**
- Digital signage infrared remote control & automation
- Home Automation & remote control
- Media remote control & automation systems

**How It works?**

Brickz listens for PRONTO HEX infrared codes via USB<>Serial or Bluetooht, simply connect to brickz via Bluetooth or USB open a terminal and type in the PRONTO code and hit enter, the command will be blasted through Brickz.If you are using Brickz with Android you can check out the example open source application that comes with brickz for sending pronto HEX codes. For detailed examples and usage, please refer to Brickz User's Manual, available in this repo.

On MAC OS X and GNU Linux once you pair with Brickz you can send PRONTO HEX codes directly from the console or via a bash script. This gives you the ability to make automation using script or controlling infrared devices directly from the console, from a script or scheduling infrared commands via cron. On MS Windows you can use any terminal application such as realterm or putty to send infrared commands with Brickz.

**Product website and Documentation**

- [Brickz official product Website](https://irdroid.eu/product/brickz)
- Documentation, Schematics, Production files and Software for Brickz can be found in this repository.

**You want to help with the development?**

- Write us an email to info@irdroid.com
