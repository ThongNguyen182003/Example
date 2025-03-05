# Branch List in the Repository
 
## Each item corresponds to a branch—information about the source code contained in that branch.

1. **main**  
   - Infomation about branch

2. **hardware-devices-emulator**  
   - Contains source code to emulate hardware devices on Linux.  
   - Useful for testing without needing actual hardware.

3. **ixy**  
   - Source code for a high-performance user-space network driver.  
   - Used for research and experimentation with the ixy network driver.

4. **linux-devce-driver-example**  
   - Demonstrates how to write device drivers on Linux.  
   - Illustrates basic driver-building processes and relevant APIs.

5. **simple-fs**  
   - Contains an example of a simple filesystem.  
   - Useful for learning how to manage data at the kernel level.

6. **usb-device-driver-example**  
   - Example of a USB device driver.  
   - Shows how to interact with USB devices on Linux, from detection to packet handling.

7. **xv6-riscv-os**  
   - The xv6 operating system Unix-like.  
   - Codebase 10k line.
   - Intended for educational and OS development research.


7. **can-driver**  
    - An open-source CAN bus driver for Linux that includes sample application code for sending and receiving CAN frames using standard system calls.  
    - Useful for understanding how applications can interact with CAN hardware (or a virtual CAN) via the driver layer.  
    - [Project Page](https://gitlab.com/hjoertel/can4linux)


8. OpenPilot (by comma.ai)
- **Description**:  
  OpenPilot is an open-source advanced driver-assistance system (ADAS) that provides semi-autonomous driving features. It integrates AI-based perception (using deep learning models), user-space applications (dashboard, control interfaces, and monitoring tools), and low-level drivers (including CAN bus communication) to interact with vehicle hardware.
- **Key Features**:  
  - **AI Modules**: Implements neural networks for lane detection, object recognition, and decision making.
  - **User-Space Applications**: Provides graphical user interfaces for monitoring and controlling the driving system.
  - **Drivers & Hardware Interface**: Uses kernel driver modules to communicate with the vehicle’s CAN bus and other hardware components.
- **Repository**: [OpenPilot GitHub Repository](https://github.com/commaai/openpilot)


9. Apollo (by Baidu)
- **Description**:  
  Apollo is a full-featured autonomous driving platform designed for real-world applications. It covers every layer of the software stack—from AI-based perception and planning to control and hardware interfacing, including sensor and actuator drivers.
- **Key Features**:  
  - **AI & Perception**: Leverages state-of-the-art machine learning and computer vision algorithms for accurate environment perception.
  - **User-Space Tools**: Offers simulation, visualization, and monitoring applications to aid development and deployment.
  - **Drivers & Hardware Interface**: Integrates extensive hardware drivers for sensors and vehicle components, ensuring robust communication with the underlying hardware.
- **Repository**: [Apollo GitHub Repository](https://github.com/ApolloAuto/apollo)

10. htop
- **Repository**: [Apollo GitHub Repository](https://github.com/htop-dev/htop)
- htop is a cross-platform interactive process viewer.
- htop allows scrolling the list of processes vertically and horizontally to see their full command lines and related information like memory and CPU consumption. Also system wide information, like load average or swap usage, is shown.








