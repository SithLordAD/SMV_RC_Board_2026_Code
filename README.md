# SMV Rear Control Board Testbench

Currently in development. There are pin mapping conflicts for the tail lights, brake lights, and turn signal light 1 (uses pins that are auto-claimed by STM32 for certain built in functions)

# Pin Mapping
| Name | Pin |
| -------- | -------- |
| ADC Chip Select | PB4 |
| Turn Signal Light 2 | PB7 |
| CAN Transmitter | PB8 |
| CAN Receiver | PB9 |
| Accelerometer Chip Select | PB12 |
| Serial Clock | PB13 |
| MISO | PB14 |
| MOSI | PB15 |
| Tail Lights | PA13 (conflict) |
| Turn Signal Light 1 | PA14 (conflict) |
| Brake Lights | PH1 (conflict) |
