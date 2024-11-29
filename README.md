# Building a High-Performance Wi-Fi Patch Antenna

<p align="center">
    <img src="https://img.shields.io/badge/language-CAD-%23ff5722.svg?style=for-the-badge&logo=autodesk" alt="CAD">
    <img src="https://img.shields.io/badge/format-DXF-blue.svg?style=for-the-badge&logo=autodesk" alt="DXF">
    <img src="https://img.shields.io/badge/format-STL-red.svg?style=for-the-badge&logo=solidworks" alt="STL">
    <img src="https://img.shields.io/badge/format-Simulation-yellow.svg?style=for-the-badge&logo=cst" alt="Simulation">
</p>

## :open_book: Project Overview

This repository contains resources for building a Wi-Fi patch antenna designed to optimize the network performance of a desktop PC. The project explores the design, simulation, fabrication, and testing of the antenna. You'll find DXF files for antenna designs, STL files for 3D-printed enclosures, and simulation files used during the design phase.

### Features

- **DXF Files**: 2D design files for PCB fabrication.
- **STL Files**: 3D models for printing the antenna enclosure.
- **Simulation Files**: Data and configurations from CST Studio used to optimize the antenna design.

---

## :link: Explore the Full Project

For a detailed walkthrough of the project, including step-by-step design, simulation, and testing of the Wi-Fi patch antenna, check out the full article:

<p align="center">
    <a href="https://hugotronics.github.io/diy-high-performance-wifi-patch-antenna/" target="_blank">
        <img src="https://img.shields.io/badge/Read%20the%20Full%20Article-%230084ff.svg?style=for-the-badge&logo=read-the-docs" alt="Read the Full Article">
    </a>
</p>

This article includes:

- **In-depth Design Process**: Insights into the choices behind the patch antenna.
- **Simulation Insights**: Detailed results and optimization tips.
- **Fabrication Guide**: Step-by-step instructions for building the antenna and its enclosure.
- **Performance Testing**: Real-world tests and measurable improvements.

---

## :rocket: Getting Started

### Files Included

1. **DXF File**:
    - `Antenna\DXF\Antenna_Patch`: Top design of the antenna for PCB milling.

2. **STL Files**:
    - `Antenna Case\STL-SOLIDWORK\Wifi_Antenna_Enclosure`: 3D model for the antenna's enclosure.
    - `Antenna Case\STL-SOLIDWORK\Wifi_Antenna_Cover`: 3D model for the enclosure cover.

3. **Simulation Files**:
   - `CST Studio Design\Patch_Antenna.cst`: CST Studio simulation files used to test and optimize the antenna's performance.

---

### How to Use

1. **Download the Files**:
   - Clone this repository or download the files directly from the [GitHub repository](https://github.com/HugoTronics/WiFi-Patch-Antenna-Project).

2. **Open DXF Files**:
   - Use a CAD software like AutoCAD or Fusion 360 to view and modify the DXF files for PCB manufacturing.

3. **3D Print STL Files**:
   - Use any 3D printer compatible with STL files to print the antenna's enclosure. Recommended material is PETG for durability.

4. **Simulate with CST Studio**:
   - Load the CST Studio simulation file to perform your own design and optimization checks.

---

## 🛠️ Installation and Setup

1. **Antenna Design**:
   - Import the DXF file into your PCB design software and prepare it for milling.

2. **3D Printing**:
   - Open the STL file in your 3D printing software and adjust settings according to your printer's specifications. Print the enclosure.

3. **Simulation**:
   - Open the CST Studio file to explore simulation results and optimize the design as needed.

---

## :test_tube: Testing and Validation

1. **Fabrication**:
   - Fabricate the antenna using the DXF design files and assemble it with the 3D-printed enclosure.

2. **Performance Testing**:
   - Test the antenna's performance using a vector network analyzer (VNA) and compare it with the simulation results.

3. **Real-World Testing**:
   - Install the antenna and measure the signal strength improvement using tools like Acrylic Suite.

---

## :memo: Documentation and References

- **CST Studio Suite**: For antenna design simulations.
- **Acrylic Suite**: For network performance measurement.
- **Vector Network Analyzer (VNA)**: For performance validation.

---

## :wrench: Future Improvements

- Add dual-band support for the 5 GHz range alongside 2.4 GHz.
- Optimize the antenna's design based on real-world feedback.
- Develop a more compact version for IoT or other specialized applications.

---

## :mailbox: Contact and Support

For questions or support, please open an issue on this GitHub repository or contact [corsahu@gmail.com](mailto:corsahu@gmail.com).

---

## :book: Additional Resources

- [Wi-Fi Antenna Design Basics](https://www.wikihow.com/Design-a-Simple-Antenna)
- [Patch Antenna Calculator](https://www.everythingrf.com/tools/microstrip-patch-antenna-calculator)
- [CST Studio Documentation](https://www.3ds.com/products-services/simulia/products/cst-studio-suite/)

---
