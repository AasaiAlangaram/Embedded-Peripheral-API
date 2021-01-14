In PIC, most of the microcontrollers has three registers for controlling their Digital I/O.

These registers are:

**TRIS** - Data Direction register\
**PORT** - Reads the levels on the pin\
**LAT** - Output Write

Here, we're going to write an API for GPIO. It consists of an initialization function, a read, write and toggle function.

GPIO Initialization:
`
void Dio_Init( const Dio_ConfigType *config);
`
