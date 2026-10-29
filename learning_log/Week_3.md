### Learnings

### AnalogRead()
- An analog pin will give you a value between **0 and 1023**, where **0 means 0V** and **1023 means the maximum voltage possible (5V by default)**
- you can only use AnalogRead() on Analog pins

**PWM - Pulse-Width Modulation**
- digital method of controlling analog power by switching on and off rapidly
- 0–255 : 0v - 5v (8 bits)
- It is a widely used technique in dimming LEDs, controlling motor speed, etc
- can be displayed with an oscilloscope

- Different Arduino pins
- We used gnd pin, 3.3 and 5V
- red button resets, doesnt delete code but reruns it
- Reset pin → possibility of automatic reset
- AREF - Analog reference pin
- Yellow (SCL; SDA etc)
  → communication between other boards
- we usually dont use pin 1 or 0

**Tilt switch**

<img width="300" height="400" alt="84072" src="https://github.com/user-attachments/assets/81d76e96-24d2-421d-ba40-f507e1571cbb" />

- component that detects object tilting
- prevent floating (unconnected) pins
- when stable: tilt sensor reading 0

**Potentiometer**
- adjustsable resistor
- commonly used in volume adjustment
<img width="300" height="400" alt="20261027_121643" src="https://github.com/user-attachments/assets/611bd8f5-65c3-45e7-9e85-0845fd3ad4f6" />

**Exercises**
- Connect Tilt switch, use serial Monitor to read output
- Connect Potentiometer and use it to dim an LED light
