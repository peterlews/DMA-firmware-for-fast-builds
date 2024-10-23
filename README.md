# DMA OL

**DMA OL** is a fast, integrated tool for creating DMA firmware. Leveraging Vivado Cloud technology, it sets up an IDE environment on the server, enabling users to simulate and build firmware directly from their web browser without local configuration.

## Features

- **Basic Open-Source Version**: Supports basic games like EAC.
- **Professional Version**: Includes support for additional simulation types such as FACEIT, VGK, and ACE (premium access required).

## Server Specifications

- **Model**: Ecs.gni2.3xlarge
- **CPU**: 14 vCPUs
- **Memory**: 56 GB
- **GPU**: A10 x 1
- **Storage**: 24 GB

## Getting Started

1. **Prepare a Server**: Set up an appropriate server environment.
2. **Run the Installation Program**: Follow the instructions to install DMA OL.
3. **Join Our Community**: For support and discussions, join our [Discord community](https://discord.gg/cfr6fnqA).

## Installation

For detailed installation instructions and configuration, refer to the documentation in this repository.

## Contributing

If you’d like to contribute to the project, please fork the repository and submit a pull request. For more details on contributing, check our contributing guidelines.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

If you encounter issues or need help, please reach out on our  or open an issue on GitHub.




![20240803182048](https://github.com/user-attachments/assets/14364952-f85e-4eba-bc6a-8423f76b12ba)


Base Version Modified Content:
 Basic tab:
- Number of lanes
- Maximum Link Speed
ID Tab:
- Vendor ID
- Device ID
- Revision ID
- Subsystem Vendor ID
- Subsystem ID
- Base Class Menu/Value
- Subclass Interface Menu/Value
- Interface Value
- Cardbus CIS Pointer
Columns tab:
Need to check your donor board to determine how many lines to enable
- Size Units
- Size Value
- 64-bit
- Prefetchable
Core Capabilities tab:
Attempts to match the device capability register hex to the hex on the donor board
- Maximum Payload Size
- Extended Label Field
- Extended Label Defaults
- Phantom Functions
- Acceptable L0s Delay
- Acceptable L1 Delay
Link Register Label
- ASPM Optional
- DLL Link Proactive Reporting Capability
- Target Link Speed
- Slot Clock Configuration
Interrupt tab:
- Interrupt Pins
- MSI Capability Architecture
- 64-bit address support
- Supports per-vector masks
- Supports multi-information
- MSIx Capability Architecture
Power Management tab:
- Device Specific Initialization
- D1 Support
- D2 Support
- D2 Support PME Support
EXT Functions tab:
- DSN Capabilities
- VC Capabilities
- VSEC Capabilities
- User-defined configuration features
EXT Capabilities 2 Tab:
- AER

