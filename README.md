# STM32F401RE Bare Metal Embedded Systems Programming

This repository contains examples and documentation for bare metal programming of the STM32F401RE microcontroller. Bare metal programming refers to writing code for microcontrollers without the use of an operating system or a higher level framework. This allows for more direct control over the hardware and can be useful for real-time systems or resource-constrained environments.

## Getting Started

These instructions will guide you through setting up the development environment and running the examples in this repository.

### Prerequisites

Before getting started, you will need to have the following reference documents:
- [STM32F41x Datasheet](https://www.st.com/resource/en/datasheet/stm32f401re.pdf)
- [STM32F401xB/C Reference Manual](https://www.st.com/resource/en/reference_manual/dm00096844-stm32f401xb-c-and-stm32f401xd-e-advanced-arm-based-32-bit-mcus-stmicroelectronics.pdf)
- [STM32 Nucleo-64 Board User Manual](https://www.st.com/resource/en/user_manual/um1724-stm32-nucleo64-boards-mb1136-stmicroelectronics.pdf)

Also, you will need to have the following software installed on your computer:


- A GCC toolchain for ARM Cortex-M (such as [GNU Arm Embedded Toolchain](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm))
- An Integrated Development Environment (IDE) for ARM Cortex-M (such as [Eclipse](https://www.eclipse.org/downloads/) with the [GNU ARM Eclipse Plug-ins](https://gnuarmeclipse.github.io/plugins/installation/))
- A programmer/debugger for STM32F401RE (such as [ST-Link](https://www.st.com/en/development-tools/st-link-v2.html))

### Setting up the development environment

1. Install the GCC toolchain and the IDE of your choice on your computer.
2. Clone or download the repository to your local machine.
3. In your IDE, import the example project as an existing project.
4. Configure the project settings, such as the target microcontroller, the compiler, and the linker.
5. Connect the programmer/debugger to your computer and to the STM32F401RE board.

### Running the examples

The examples in this repository include:

1. Blink LED: This basic example demonstrates how to control the output of an LED connected to a specific pin of the microcontroller.
2. UART Communication: This example shows how to set up serial communication with a PC using the UART peripheral of the microcontroller.

To run the examples:

1. Build the project by clicking on the "Build" button in the IDE.
2. Connect the programmer/debugger to the STM32F401RE board and power it on.
3. Upload the built code to the microcontroller using the programmer/debugger.
4. Use the serial communication software to interact with the examples if required.

### Note

When working on bare metal embedded systems, low level control is critical, for example, to avoid unexpected behaviours caused by missing some important step or misconfiguring some peripheral, which could lead to hard-to-diagnose bugs. Therefore, it is important to consult the chip's reference manual and the datasheet before start working with the microcontroller.

## Contributing

We welcome contributions to this repository! If you have any improvements or bugfixes, please open a pull request.

## Contact

If you have any questions or feedback, please contact me at emasicollins@gmail.com
