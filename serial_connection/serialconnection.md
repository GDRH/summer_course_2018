### Cum sa te conectezi la serial port

In prima poza, anume,![wireless](wireless_connection.jpg) ne conectam arduino-ul la calculator cu ajutorul unui wireless serial.
Ei bine, acelasi lucru il putem face cu ajutorul unui serial port precum in a doua poza ![serial](serial_port.jpg)
#### Pasii pentru conectare:

1.Legam cele 3 fire de la  serial port pe wireless module

-Galben la TXD pe serial port si pe wireless module la RX

-Albastru la RXD pe serial port si pe wireless module la TX

-Negru la GND pe ambele

2.Conectam USB-ul de la serial port la calculator si ne conectam prin mBlock la el

-Connect -> Serial Port -> COM_x

Nota: In caz de nu apare device-ul trebuie sa downloadati driverele specifice windows-ului pentru usb, driverele le gasiti aici: 

[Drivers](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers)

3.Pornim robotul si dupa putem da comenzi cu ajutorul mBlock

