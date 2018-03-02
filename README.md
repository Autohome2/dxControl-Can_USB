# dxControl-Can_USB

This project is to provide a small USB to CANBUS interface to allow Tunerstudio to connect directly to a CAN network.

The device behaves as a master and supports passthrough to other TS enabled devices on the CAN network.

At this time only devices using the Speeduino CAN network protocol can be accessed by TS through this device.

For more information on the protocol see the explanation pdf.

Some additional libraries need to be installed in order to compile this firmware within the Arduino enviroment , see the libraries folder details.

The Can USB interface uses a ... mcu at its heart . Board files for a pcb shield to add the CANBUS interface is also included in the shield folder
