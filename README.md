# VOXEL Hackpad 

A custom-engineered, high-performance mechanical macropad powered by the Seeed Studio XIAO RP2040. Designed specifically for the Hack Club hardware grant program, featuring a streamlined matrix layout, a 3D-printed multi-part enclosure, and custom PCB architecture.

---

## 🛠️ Bill of Materials (BOM)

| Component | Quantity | Description / Notes |
| :--- | :---: | :--- |
| **Seeed Studio XIAO RP2040** | 1 | Microcontroller / Brain |
| **Mechanical Switches** | 4 | MX-style mechanical switches |
| **Keycaps** | 4 | Compatible keycaps |
| **3D Printed Case (Top)** | 1 | PLA/PETG Enclosure Cover |
| **3D Printed Case (Interior/Bottom)** | 1 | PLA/PETG Enclosure Base |

---

## 📁 Repository Structure

* **`/CAD`**: Master 3D assembly `.3mf` file.
* **`/PCB`**: Native KiCad source design files (`.kicad_pro`, `.kicad_sch`, `.kicad_pcb`).
* **`/Firmware`**: Raw source code mapping the matrix and logic.
* **`/production`**: Manufacturing package containing `gerbers.zip`, compiled `firmware.uf2`, and individual case `.stl` exports.

---

## 📜 License
Licensed under the terms of the [MIT License](LICENSE).
