# Unitree Robot SDK Version 2
Unitree Robot SDK Version 2 is a comprehensive software development kit designed to provide a robust and efficient way to interact with Unitree robots. This SDK is built on top of a robust tech stack, including C++, CMake, and various libraries such as Eigen, Boost, and spdlog.

## Project Description
The Unitree Robot SDK Version 2 is designed to provide a unified interface for controlling and interacting with Unitree robots. It provides a set of APIs and tools that enable developers to create custom applications, integrate with other systems, and leverage the capabilities of Unitree robots. The SDK is built with a focus on performance, reliability, and ease of use, making it an ideal choice for a wide range of applications, from research and development to industrial automation and robotics.

## Tech Stack
The Unitree Robot SDK Version 2 is built using a combination of the following technologies:
* **Programming Languages:** C++, Python
* **Build System:** CMake
* **Libraries:** Eigen, Boost, spdlog, yaml-cpp
* **Dependencies:** GCC, Make, libeigen3-dev, libboost-all-dev, libspdlog-dev, libfmt-dev

## Installation and Startup
To install and start using the Unitree Robot SDK Version 2, follow these steps:
### Prerequisites
* **OS:** Ubuntu 20.04 LTS
* **CPU:** aarch64 and x86_64
* **Compiler:** GCC version 9.4.0
* **Dependencies:** CMake, GCC, Make, libeigen3-dev, libboost-all-dev, libspdlog-dev, libfmt-dev

### Install Dependencies
```bash
apt-get update
apt-get install -y cmake g++ build-essential libyaml-cpp-dev libeigen3-dev libboost-all-dev libspdlog-dev libfmt-dev
```

### Build and Install the SDK
```bash
mkdir build
cd build
cmake ..
make
sudo make install
```
Alternatively, you can install the SDK to a custom directory:
```bash
mkdir build
cd build
cmake .. -DCMAKE_INSTALL_PREFIX=/opt/unitree_robotics
sudo make install
```

## Basic Usage
The Unitree Robot SDK Version 2 provides a set of APIs and examples to get you started. Here are a few examples:
* **State Machine:** The `example/state_machine` directory contains an example of how to use the state machine API.
* **H1 Parallel Mechanism Control:** The `example/h1` directory contains an example of how to control the H1 parallel mechanism.

### API Examples
The SDK provides a range of APIs for controlling and interacting with Unitree robots. Here are a few examples:
* **Feedforward Torque:** `tau`
* **Target Angle:** `q`
* **Target Angular Velocity:** `dq`
* **Joint Stiffness:** `kp`
* **Joint Damping:** `kd`

## Contributing
The Unitree Robot SDK Version 2 is an open-source project, and we welcome contributions from the community. To contribute, please fork the repository, make your changes, and submit a pull request.

## Licensing
The Unitree Robot SDK Version 2 is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

## Additional Resources
For more information, please visit the [Unitree Document Center](https://support.unitree.com/home/zh/developer).