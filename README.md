# LIS3DSH_demo
An application demo for STM32F4Discovery board using libopencm3 library. This demo uses the 3-axis accelerometer LIS3DSH and the LEDs on the board.

For compiling the project it is necessary to download the libopencm3 library. This project folder must be located in the same folder where libopencm3 is located. For compiling the project run:

    $ make

and for flashing the STM32F4Discovery board run:

    $ make flash

The default toolchain the same of libopencm3, a arm-none-eabi/arm-elf toolchain.

