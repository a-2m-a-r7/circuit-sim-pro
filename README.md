# CircuitSim Pro - Physics Circuit Simulator

[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows&logoColor=white)](https://microsoft.com)
[![Runtime](https://img.shields.io/badge/.NET-9.0-512BD4?logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Framework](https://img.shields.io/badge/Framework-WPF-blue)](https://docs.microsoft.com/dotnet/desktop/wpf/)
[![Category](https://img.shields.io/badge/Category-Physics%20Simulation-purple)](#features)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

An interactive Windows desktop physics simulation tool designed for modeling electrical circuits, measuring electrical parameters in real time, and visualizing Ohm's law and circuit behavior.

---

## Features

- **Interactive Circuit Canvas:** Draw and wire custom electrical circuits with intuitive controls.
- **Circuit Components:** Supports batteries/power sources, resistors, switches, lamps, and measurement instruments.
- **Live Electrical Metering:** Real-time ammeter (Current $I$) and voltmeter (Voltage $V$) displays with precise digital readout.
- **Dynamic Physics Calculations:** Step-by-step breakdown of Ohm's Law ($V = I \times R$), equivalent resistance, power dissipation, and individual lamp states.
- **Current vs. Time Graph:** Oscilloscope-style real-time signal canvas plotting current fluctuations over time.
- **Modern WPF Interface:** Clean desktop design with high-contrast displays and smooth responsive controls.

---

## Tech Stack

- **Language:** C#
- **UI Framework:** WPF (Windows Presentation Foundation)
- **Target Runtime:** .NET 9.0 Desktop Runtime (`Microsoft.WindowsDesktop.App`)
- **OS Support:** Windows 10 / Windows 11

---

## Getting Started

### Prerequisites

Ensure you have the [.NET 9.0 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/9.0) installed on your Windows machine.

### Running the Application

1. Clone or download this repository.
2. Launch `CircuitSimPro.exe` directly from the project directory.

```powershell
.\CircuitSimPro.exe
```

---

## Repository Structure

```text
Projct Phsics 3/
├── CircuitSimPro.exe                    # Application executable launcher
├── CircuitSimPro.dll                    # Compiled physics simulator assembly
├── CircuitSimPro.runtimeconfig.json     # .NET 9.0 runtime configuration
├── CircuitSimPro.deps.json              # Dependency mapping
├── CircuitSimPro.pdb                    # Debug symbol database
├── .gitignore                           # Git ignore rules
├── LICENSE                              # MIT License
└── README.md                            # Documentation
```

---

## License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.
