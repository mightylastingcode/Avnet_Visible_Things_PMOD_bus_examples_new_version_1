# Avnet_Visible_Things_PMOD_bus_examples_new_version_1
New examples for PMOD Configuration for Avnet Visible Things (Renesas S7G2 based Kit)

PMOD examples (GPIO input, GPIO output, SPI, I2C, and UART) for S2G7 based Avnet Visible Thing Gateway Evaluation Board

Note: PMOD ports are configured through the PCA9535 chip on the Avnet board.

Project RTOS based Examples: 

gw002_example_gpio_12pin_rtos_v1b.zip   - GPIO Type 1, 12 pins (how to set pins as input or output pins)
gw002_example_gpio_6pin_rtos_v1a.zip    - GPIO Type 1, 6 pins  (how to set pins as input or output pins)
gw002_example_i2c_rtos_v1e.zip          - I2C 4 pins (read the voltage level from a potentiometer)  
gw002_example_spi_rtos_v1a.zip          - SPI Type 2 6 pins (read xyz, and device ID)  
gw002_example_uart_rtos_v1d.zip         - UART Type 4, 6  pins (Print the PMOD2 input pattern on PC serial term) 
gw002_example_gpio_i2c_spi_uart_v1h.zip - Combine GPIO, SPI, I2C and UART examples together

All the pdf files contain the information on the Renesas project configuration as well as what output result to expect from these examples.   Hardware setup diagrams are included.

In the document folder are:

1. Digilent PMOD Interface Spec
2. PCA9535 IO Expander IC Chip Datasheet
3. ADS 1015 Analog to Digital IC Chip Datasheet
4. Renesas BMC150 Module Datasheet
5. Bosh BMC150 Accelerometer Datasheet
