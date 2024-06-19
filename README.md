# AgroWise--Smart-Irrigation 🌱💧

## Overview

**AgroWise** is an intelligent irrigation system designed to optimize water usage in agricultural fields by utilizing an 8051 microcontroller. This project includes a circuit diagram, Proteus simulation files, a detailed MPMC (Microprocessor and Microcontroller) report, and the source code in a `.hex` file format. The system ensures efficient irrigation management, reducing water wastage and enhancing crop yield.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Description

AgroWise is built around the 8051 microcontroller and is aimed at automating irrigation based on soil moisture levels and environmental conditions. The system uses sensors to monitor soil moisture and accordingly controls water flow to maintain optimal moisture levels for various crops. 

### Key Components

- **8051 Microcontroller**: The heart of the system, responsible for processing sensor inputs and controlling outputs.
- **Sensors**: Used to measure soil moisture and environmental conditions.
- **Relay Module**: Controls the water pump based on the microcontroller's signals.
- **Proteus Simulation**: Provides a virtual environment to simulate and test the circuit.
- **MPMC Report**: Detailed documentation of the project, covering the system's design, functionality, and testing.
- **.hex File**: The compiled code for the 8051 microcontroller.

## Features

- **Automatic Irrigation**: Adjusts water supply based on real-time soil moisture data.
- **Efficient Water Usage**: Reduces water wastage by ensuring irrigation only when necessary.
- **Easy Monitoring**: Real-time monitoring of soil conditions and system status.
- **Simulation and Testing**: Pre-validated circuit design and functionality using Proteus.

## Project Structure

```plaintext
AgroWise--Smart-Irrigation/
│
├── CircuitDiagram/
│   ├── AgroWise_Circuit.pdsprj  # Proteus project file
│   └── AgroWise_Circuit.png     # Circuit diagram image
│
├── Code/
│   ├── AgroWise_Main.hex        # Compiled hex file for 8051 microcontroller
│   └── AgroWise_Code.c          # Source code in C
│
├── Documentation/
│   └── MPMC_Report.pdf          # Detailed project report
│
├── README.md                    # Project README file
└── LICENSE                      # Project license file
```

### Note: The document names might have been changed.


## Getting Started

### Prerequisites

- **Proteus Software**: Required to open and simulate the circuit diagram.
- **8051 Microcontroller Programmer**: To upload the `.hex` file to the microcontroller.
- **Basic Electronics Knowledge**: Understanding of microcontrollers, sensors, and circuit design.

## Installation and Setup

1. **Download and Install Proteus**:
   - Obtain Proteus from the official website and install it on your computer.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/msnabiel/AgroWise--Smart-Irrigation.git
   cd AgroWise--Smart-Irrigation
   ```

3. **Open the Circuit Diagram in Proteus**:
   - Navigate to the `CircuitDiagram` directory and open `AgroWise_Circuit.pdsprj` in Proteus.

4. **Load the `.hex` File**:
   - Use a microcontroller programmer to upload `AgroWise_Main.hex` from the `Code` directory to your 8051 microcontroller.

5. **Review the Project Report**:
   - Open `MPMC_Report.pdf` in the `Documentation` directory for detailed information on the project.

## Usage

1. **Simulate the Circuit**:
   - Run the simulation in Proteus to observe the circuit's functionality. You can test different soil moisture levels and see how the system reacts.

2. **Deploy on Hardware**:
   - Connect the components as per the circuit diagram and upload the `.hex` file to the 8051 microcontroller. Test the system in a real-world environment.

3. **Monitor and Adjust**:
   - Use the system to monitor soil moisture and control irrigation. Adjust sensor thresholds as necessary to suit different crops or environmental conditions.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Please see the [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- **GitHub**: [msnabiel](https://github.com/msnabiel)
- **Email**: [msyednabiel@gmail.com] (https://github.com/msnabiel)
- **LinkedIn**: [msnabiel](https://www.linkedin.com/in/msnabiel/)

Thank you for checking out the **AgroWise--Smart-Irrigation** project! Feel free to reach out for any questions or collaboration opportunities.
