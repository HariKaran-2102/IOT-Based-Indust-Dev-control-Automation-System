# IoT Based Industrial Device Control and Automation System

This project is an **IoT-based device control and automation system** developed to control four electrical bulbs remotely using the Internet.

The system uses an **LPC2129 microcontroller** as the main controller and an **ESP8266 NodeMCU** for Wi-Fi connectivity. **Arduino Cloud** is used to send ON/OFF commands remotely. A **4-channel relay module** is used to control the four bulbs independently.

## Block Diagram

<img width="1145" height="1374" alt="image" src="https://github.com/user-attachments/assets/e97d86d1-1670-41d2-a877-7615fde29c39" />


## Hardware Used

| Component              | Purpose                     |
| ---------------------- | --------------------------- |
| LPC2129                | Main microcontroller        |
| ESP8266 NodeMCU        | Wi-Fi and IoT communication |
| 4-Channel Relay Module | Controls the four bulbs     |
| Four Bulbs             | Electrical loads            |
| Power Supply           | Provides required power     |
| Connecting Wires       | Circuit connections         |

## Software Used

* Arduino Cloud
* Embedded C
* ESP8266 Programming Environment

## Working

1. The user gives an **ON/OFF command** through Arduino Cloud.
2. The command is received by the **ESP8266 NodeMCU** through the Internet.
3. The ESP8266 sends the command to the **LPC2129**.
4. The LPC2129 processes the command.
5. The corresponding relay channel is activated or deactivated.
6. The selected bulb is switched **ON or OFF**.

### Control Example

```text
Bulb 1 ON → Relay 1 ON
Bulb 2 ON → Relay 2 ON
Bulb 3 ON → Relay 3 ON
Bulb 4 ON → Relay 4 ON
```

The same process is followed for turning the bulbs OFF.

## Features

* Remote control through the Internet
* Independent control of four bulbs
* Wi-Fi connectivity using ESP8266
* LPC2129-based control
* Arduino Cloud integration
* Simple and low-cost implementation
* Can be expanded for additional devices

## Applications

* Industrial device control
* Smart home automation
* Office automation
* Laboratory automation
* Remote electrical load control
* IoT and embedded-system projects

## Future Improvements

The project can be extended by adding:

* Sensors
* Automatic scheduling
* Energy monitoring
* Real-time device status
* Mobile application control
* More electrical and industrial devices

## Conclusion

This project demonstrates the use of **IoT and embedded systems for remote electrical device control**. The combination of **Arduino Cloud, ESP8266, LPC2129, and a 4-channel relay module** provides a simple method for controlling multiple electrical loads remotely.

The system can be further developed into a more advanced **IoT-based industrial automation platform**.

