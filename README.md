This series lecture will cover my work porting some of the tools used to develop **IKARUS project**.  
I am moving from **AVR** to **ARM** to provide the system with more powerful capabilities such as

* More IO pins
* Speed up to 72 MHz
* **RTOS**
* More peripherals
* More **RAM** and **FLASH**
* **CubeMX IDE** , fully dedicated IDE to use ST's **HAL and LL libraries** with init **code generation**
* **Dedicated USB device communication** with multiple modes  of operation.

The microcontroller of choice is the well known **STM32F103C8T6** found in BLUEPILL because it's **good, pretty and cheap** -even cheaper than the microcontroller itself.
  
The goal is to put together a device capable of

- [ ] USB communication as devise , to receive orders from a computer.
- [x] Accurately control servos, main actuators in IKARUS project.
- [x] I<sup>2</sup>C to communicate with other devices. e.g: MPU6050
- [ ] SPI , also to communicate with other devices. e.g: dedicated display

This is my first attempt ever to share some knowledge, all constructive suggestions are welcome at  arreguez.joaquin@gmail.com .

---

 I hope this can be useful to anybody that´s out there trying to understand and have fun with electronics!!