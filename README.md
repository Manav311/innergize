𝙄𝙣𝙣𝙚𝙧𝙜𝙞𝙯𝙚 𝙁𝙞𝙧𝙢𝙬𝙖𝙧𝙚 𝙛𝙤𝙧 𝙣𝙍𝙁52840

About the Project
Innergize Firmware is specifically designed for the nRF52840 smart patch hardware device, which aids in relaxation through stimulation. This firmware allows the smart patch to interface seamlessly via Bluetooth with the Innergize mobile application. The main functions include managing Bluetooth connectivity, handling device configuration, and processing data received from sensors.

FEATURES

Bluetooth Connectivity: Manages seamless communication with the Innergize application.
Sensor Data Processing: Acquires and processes data from various sensors integrated into the smart patch.
Energy Efficiency: Optimized for low power consumption to extend the battery life of the device.
User Data Management: Handles user-specific settings and preferences.

Getting Started

Prerequisites
To work on this project, you need:

NRF Connect SDK for nRF52840

ARM GCC Compiler

VS CODE IDE

INSTALLATION

Clone the repository:

bash
Copy code

git clone https://github.com/Innergize-healthcare/innergize-firmware

Navigate to the project directory:

bash
Copy code
cd innergize-firmware

Build and Flash
To build the firmware and flash it to the nRF52840 device, follow these steps:

Open the project in VS CODE IDE

Install the nrf connect sdk for vs code 2.4.0

Build the project by selecting Build 

Connect your nRF52840 development kit via USB.

Flash the firmware by selecting Flash 

USAGE   

Ensure the smart patch device is powered and in Bluetooth range.

The firmware will automatically initialize and start communication with the paired Innergize application.

Development Environment
Set up your development environment by installing the Nordic SDK 

Configure your IDE to use the ARM GCC Compiler.

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.

Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -am 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a pull request.


License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments

Nordic Semiconductor for providing the SDK.
All contributors who participate in the development of Innergize Firmware.
