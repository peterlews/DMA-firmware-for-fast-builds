DMA OL
DMA OL is a fast and integrated tool designed for creating DMA firmware. Leveraging Vivado Cloud technology, it quickly sets up an IDE environment on the server, enabling efficient simulation and firmware creation directly from your web browser—no local environment configuration required!

Current Progress
As of now, we offer a basic open-source version of DMA OL. This version supports a limited range of applications, including basic eac and other games. Advanced features, such as support for VGA and Faceit, are available in the premium version.

Server Specifications
Model: Ecs.gni2.3xlarge
CPU: 14 vCPUs
Memory: 56 GB
GPU: A10 x 1
Storage: 24 GB
Build Mode
To build and run DMA OL, you need to prepare a server and execute the installation program. If you encounter any issues or have questions, you can join our Discord community for support and discussion: Join Discord.

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

