# about pytheas
Pytheas is a custom ATSAMD21G18A-based (Cortex-M0+, arduino-compatible) flight controller which I have designed for a self-landing, thrust vectoring rocket which is being built by ![Princeton Rocketry](https://www.princetonrocketry.com/) at Princeton University. Anyone is welcome to integrate it into their projects as long as they provide appropriate credit. However, no technical support is provided.

# features
 - ATSAMD21G18A microprocessor
   - Programmable via SWD (TagConnect, half-pitch DuPont) and USB
   - 10 exposed GPIO (plus 5 more extras in half-pitch)
   - Exposed I2C
   - Everything else you'd expect
 - BMP390 Pressure Sensor
 - LSM6DSOXTR 9-Axis IMU
 - Power Regulation:
   - 5V @ 9A out (buck) with lots of capacitence  
   - 3v3 @ 1A out (LDO)
   - ~6–12V in

# layers
![layers image](/pytheas_layers.png)
