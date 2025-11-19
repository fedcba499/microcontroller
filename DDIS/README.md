## List of components
- MicroPython
- ESP32 Module
- HC SR04 Ultrasonic Sensor
- Relay Switch (Looking for alternate with compact size)
- Power Source (9V Battery)

## Which Sensor used for Distance Measuring?
HC SR04 Ultrasonic sensor, it uses sound waves to measure distance. it can measure distances upto 8 meters.

## Does HC SR04 work with 3.3 V?
According to the datasheet, it cannot be powered from 3.3V but what you can do is trigger the module with 3.3V and in the echo line use a suitable voltage divider to drop the voltage to 3.3V.
