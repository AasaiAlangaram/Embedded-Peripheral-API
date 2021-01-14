In PIC, most of the microcontrollers has three registers for controlling their Digital I/O.

These registers are:

**TRIS** - Data Direction register\
**PORT** - Reads the levels on the pin\
**LAT** - Output Write

**Gneric IO PORT From PIC16F1828 Datasheet**
![Gneric IO PORT From PIC16F1828 Datasheet](https://github.com/AasaiAlangaram/Embedded-Peripheral-API/blob/main/Microchip/GPIO/Generic_IO_PIC16F1828.JPG)

Here, we're going to write an API for GPIO. It consists of an initialization function, a read, write and toggle function.

GPIO Initialization:
`
void Dio_Init( const Dio_ConfigType *config);
`
