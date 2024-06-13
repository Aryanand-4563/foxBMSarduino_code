# foxBMSarduino_code
CODE CONTAINS ALL THE FUNCTIONALITIES REQUIRED FOR FOXBMS SYSTEM USING AN ARDUINO 
Features include:-
ADC initialization and reading(helps to convert all the sensors values to convert in digital value for eg, temperatures sensors, voltage sensors)

SPI communication(To facilitate communication between the main microcontroller and various peripheral devices.)

EEPROM for Backup SRAM(Electrically Erasable Programmable Read-Only Memory helps to keep the data stored even if the power is turned off typically used to store configuration parameters, calibration data, state of charge (SOC) values, and other critical data that must be retained between power cycles.)

UART Communication with FreeRTOS Support( Universal Asynchronous Receiver/Transmitter communication used for data exchange between the main microcontroller and other devices or modules, such as a PC for debugging, monitoring tools, or other microcontrollers and in combination with freeRTOS UART communication can be handled efficiently in a real-time operating system, enabling better task management and responsiveness)

FreeRTOS and Interrupt Handling(VIC - Vectored Interrupt Controller)(enhance the responsiveness and efficiency of the system. FreeRTOS allows for concurrent task execution, while interrupts can handle time-critical events without waiting for the main loop to process them)










