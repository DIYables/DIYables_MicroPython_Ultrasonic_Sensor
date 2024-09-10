## MicroPython Ultrasonic Sensor Library - DIYables_MicroPython_Ultrasonic_Sensor
This MicroPython Ultrasonic Sensor library is designed for any hardware platform that supports MicroPython such as Raspberry Pi Pico, ESP32, Micro:bit... to make it easy to use with ultrasonic sensor. It is easy to use for not only beginners but also experienced users... 

It is created by DIYables to work with DIYables Ultrasonic Sensor, but also work with products from other brands. Please consider purchasing products from [DIYables Store on Amazon](https://www.amazon.com/dp/B0BDFLPZ2R) to support our work.



Features
----------------------------
* Works with any hardware platform that supports MicroPython such as Raspberry Pi Pico, ESP32, Micro:bit...
* Supports the noise filter  (filtering noise from enviroment, ultrasonic interference...)
* Supports detection threshold. If distance > threshold, the library will not consider any object detected.


Available Functions
----------------------------
* \_\_init\_\_(trig_pin, echo_pin)
* set_detection_threshold(distance)
* enable_filter(num_samples=20)
* disable_filter()
* loop()
* get_distance()


Available Examples
----------------------------
* main.py



Tutorials
----------------------------
* [Arduino MicroPython - Ultrasonic Sensor](https://newbiely.com/tutorials/arduino-micropython/arduino-micropython-ultrasonic-sensor)
* [ESP32 MicroPython - Ultrasonic Sensor](https://newbiely.com/tutorials/esp32-micropython/esp32-micropython-ultrasonic-sensor)
* [Raspberry Pi Pico - Ultrasonic Sensor](https://newbiely.com/tutorials/raspberry-pico/raspberry-pi-pico-ultrasonic-sensor)



References
----------------------------
* [MicroPython Ultrasonic Sensor Library](https://newbiely.com/tutorials/micropython/micropython-ultrasonic-sensor-library)
