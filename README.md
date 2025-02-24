# GSP Wireless Motion Board Rev. D
**Wireless motion board for senior design at Missouri S&amp;T**

This board is designed to capture and wirelessly transmit motion data during a frisbee toss. It features an ESP32-C3-Mini-N4 microcontroller for efficient Bluetooth Low Energy (BLE) communication and an ICM-42670 high-precision 6DOF IMU for real-time motion tracking.

The primary goal of this project is to analyze key motion parameters of a frisbee throw, including initial spin rate (RPM), launch angle, stability, and acceleration. The ICM-42670 provides high-resolution accelerometer and gyroscope data, which allows for precise measurement of motion dynamics.

This design improves upon previous iterations by optimizing power efficiency and reducing form factor for future iterations. The onboard TLV62569DBVT switching regulator ensures stable power delivery to both the ESP32 and IMU. The compact size and BLE connectivity make this an ideal prototype for real-world frisbee motion analysis, with potential applications in sports analytics, biomechanics research, and performance optimization.

Schematic design by Josue Cavazos and Andrew Thomas

PCB Design led by Josue Cavazos

---

### What you'll find in this repository:
- Hardware designs (made in KiCad)
- Reference designs
- Device datasheets
- Circuit simulations

---

### Repository Project Structure:
- *3D Models* - Models for PCB components not found in the standard KiCad library
- *BOM* - An interactive HTML bill of materials (generated from the *Interactive HTML BOM* Plugin)
- *Datasheets* - Datasheets for specific devices used, such as the buck converter, transistors, battery charger, etc.
- *Docs* - Reference schematics used in the circuit design phase
- *Images* - High quality renderings of the final PCB in 3D
- *Libraries* - Folders to include schematic symbols and footprints for components not found in the standard KiCad library
- *Schematics* - PDFs of entire PCB schematic
- *Simulations* - LTSpice simulation block with any custom component libraries
- KiCad hardware design files