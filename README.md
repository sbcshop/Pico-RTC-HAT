# Pico-RTC-HAT
Pico RTC HAT is a Real-Time clock expansion module with the powerful IC DS3231, backup battery holder, operating voltage 3.3 V, and Fast (400kHz) I2C Interface that measures the time which aligns the time of the device with the “Real-Time”.


## How to use ?

### Board Details :

* DS3231 SDA - PICO GP6
* DS3221 SCL - PICO GP7


### Requirements

* Raspberry Pi Pico RTC HAT: (Buy it from : https://shop.sb-components.co.uk/products/pico-rtc-hat  )
* Raspberry Pi Pico (Buy it from : https://shop.sb-components.co.uk/collections/latest-collections/products/raspberry-pi-pico-board-with-header )
* USB Cable
* Jumper Cables (optional)

### Steps :

* Stack Raspberry Pi Pico on female header of Pico RTC HAT.
* Connect USB cable on Raspberry Pi Pico USB port.
* Now use example code "RTC-HAT.py" from Pico RTC HAT's github repository in any micropython supported ide (preferred thonny ide).
* Copy paste code in ide and choose interpreter as MicroPython (Raspberry Pi pico).

<img src="https://github.com/sbcshop/Raspberry-Pi-Pico-RFID-Expansion/blob/main/images/thonny-interpreter.PNG" />

* Click on green play button to run example of Pico RTC HAT.
* To change date, time or week, change variables of below line

CurrentTime = b'\x00\x00\x01\x06\x16\x04\x21' #00:00:01 friday 16/04/2021 
