# Fault Detection in an Underground Cable using IOT
Underground cables are prone to a wide variety of faults due to underground conditions, wear and tear, rodents etc. 

The project work is intended to detect the location of fault in underground cable lines from the base station in km using a ATMEGA8 controller. IOT technology is used to display the fault occurring distance, type of fault, and time information over Internet. This prototype uses the simple concept of Ohms law. In case of fault, the voltage across series resistors changes due to change in current accordingly which is then fed to an ADC to develop precise digital data to a programmed ATMEGA8 that further displays fault location in distance. The fault occurring distance, phase, and time is displayed on a FND  interfaced with the microcontroller. IoT is used to display the information over Internet using the Wi-Fi module ESP8266. A webpage is created using HTML coding and the information about occurrence of fault is displayed in a webpage. Short Circuit and Open Circuit Fault are detected in the project.

The benefits of accurate location of fault are fast repair to revive back the power system, it improves the system performance, it reduces the operating expense and the time to locate the faults in the field.

# Project Module
The module consists of an ATMEGA8 microcontroller, Wi-Fi module ESP8266, resistors, switches, voltage divider, DC adaptor and LEDs.

![IMG20210720021455](https://user-images.githubusercontent.com/126613134/224124804-aa6b24ff-a7e7-441b-967f-1d0cbcca9128.jpg)

# Fault Detection Time,Date and Location
This webpage occurs when no fault is made through switches.

![Screenshot_2021-07-20-02-16-26-68_48cc903c601d19f5677715f40a11fc00](https://user-images.githubusercontent.com/126613134/224127162-1060a2e7-d88f-4d40-8286-87919c2e7086.jpg)

This webpage shows a short circuit fault which has occured with data showing the time, distance and date of the fault.

![Screenshot_2021-07-20-02-18-57-77_48cc903c601d19f5677715f40a11fc00](https://user-images.githubusercontent.com/126613134/224127897-19fd785b-9e93-4298-b9c3-14a9699b0aec.jpg)

This webpage shows an open circuit fault.

![Screenshot_2021-07-20-02-20-58-58_48cc903c601d19f5677715f40a11fc00](https://user-images.githubusercontent.com/126613134/224128022-30409479-4aef-402c-8d6a-f48cbdd1cc45.jpg)

