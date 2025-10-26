# Wi-Fi-controlled-car-using-NODE-MCU

The NodeMCU is an ESP-32S-based microcontroller (MCU), similar to the ATmega328P, but with built-in Wi-Fi capability.It’s an excellent platform for beginners exploring IoT projects.The ESP-32S can connect to a Wi-Fi network or even function as a hotspot. Refer to the pinout diagram above for guidance—remember that in the Arduino code, GPIO numbers are used to reference the pins.

In this setup, the NodeMCU connects to your router and obtains a local IP address. By entering this IP address into a web browser on your smartphone or computer (connected to the same router), a control webpage will appear with buttons to operate the car. This allows you to control the car wirelessly through the web interface. 

# Hardware Required 
- Node MCU WIFI ESP-32S
- Motor Driver L298N
- 4WD Smart Robot Car Kit 

- 4 DC Motor 

- 4 Wheel 

- Breadboard 400-Tie 

- 2 Battery 1800mah Battery 

- Battery Box 

- Jumper Wire 20cm 20 pcs 

- Hot Glue Gun 

- 2 Glue Sticks

- 1 Switch.

# Connections and Uploading Code

First, assemble your car chassis. Attach the motors, wheels, and caster wheel securely using screws. Solder wires to the motors and connect them to the L298N motor driver module.

Refer to the wiring diagram above and make the connections according to your setup. If this is your first time using the L298N driver, you can test your motor connections by uploading a simple Arduino code that moves the car forward. Then test right, left, and backward movements using digitalWrite() commands.

Both the NodeMCU and the L298N need power. It’s best to use separate power supplies for them. You can power the NodeMCU with 5V from a power bank (connected to the Vin and GND pins) and use a 9V or 12V battery for the L298N motor driver.

The process is simple just follow the picture and the NodeMCU pinout diagram to understand the connections clearly.
 
