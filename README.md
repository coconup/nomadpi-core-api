# VanPi core API

This project is a streamlined version of the original [VanPi OS](https://github.com/Pekaway/VAN_PI/tree/main/VanPi-OS), designed to provide essential functionality for hardware operation through an HTTP API. The primary purpose is to allow control of connected devices via any client that can interact with the API.

## Features

The current version supports the following devices, matching the hardware available:

* Relays on the relay board
* Tasmota WiFi relays
* Temperature sensors
* JBD BMS over Bluetooth
* USB GPS dongles
* Zigbee USB dongles

## Missing Components

While the current functionality covers a range of devices, there are some notable components yet to be included:

1. **Heater:** The plan is to integrate Webasto with the currently sold-out K-bus from the shop. Research has been initiated, and once the hardware is available, support for this component will be added.
2. **Tank Sensors:** Due to the absence of the required hardware, consideration is being given to replacing the existing options with Ultrasonic distance sensors. Further research is needed in this area.
3. **Shunt:** The inclusion of a shunt is currently undecided, and support for it depends on the availability of the hardware. While there is no plan to include it in the initial build, contributions for this component are welcome.

## Future Development

The project is open to expansion with additional device support. As more devices become available, the plan is to extend the range of supported hardware. Contributions from the community are highly encouraged.

## Contributing

If you have access to hardware supported by the original VanPi OS and would like to port functionality to this project, feel free to fork the repository and open a pull request. Your contributions are valuable, and collaboration is key to enhancing the project.
