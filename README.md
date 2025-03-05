<<<<<<< HEAD
# LiPo Battery Charger (Altium Design)

## Overview
This project is a **LiPo Battery Charger** designed using **Altium Designer**. The charger supports **3.7V LiPo cells** and provides charging at **500mA or 100mA**. It is designed for **single-cell Li-Ion or Li-Polymer batteries**.

![LiPo Battery Charger PCB](Images/Lipo-Charger-3D:pdf.png)

### Features
- **Charging Circuit**: Charges LiPo batteries safely.
- **Selectable Charging Rate**: Solder jumper to select **500mA or 100mA**.
- **USB Input & Barrel Jack Connector**: Multiple power input options.
- **Pre-installed JST Connectors**:
  - **SYS OUT** (for powering projects without disconnecting the charger)
  - **BATT IN** (battery input connector)
- **Status LED Indicators**: Shows charging status.
- **External LED Footprint**: Allows external status monitoring.

---

## 🔧 Hardware Requirements
- USB power source (5V, 1A recommended)
- Single-cell **3.7V LiPo Battery**
- External LED for status monitoring (optional)

## 💻 Software Requirements
- **Altium Designer** for viewing/modifying the schematic and PCB layout
- **Gerber Viewer** for fabrication file verification

---

## 🛠️ Required Files & How to Get Them
### 1. **Schematic Files (`Schematics/` Folder)**
- Export **.SchDoc** from Altium Designer.

### 2. **PCB Layout Files (`PCB/` Folder)**
- Export **.PcbDoc** from Altium Designer.

### 3. **Gerber Files (`Gerber/` Folder)**
- Go to **File > Fabrication Outputs > Gerber Files**.
- Select layers (Top, Bottom, Silkscreen, Solder Mask, Drill File).
- Click **Generate** & save.

### 4. **3D Model Files (`3D_models/` Folder)**
- Open **PcbDoc > File > Export > STEP 3D**.
- Save as `.step`.

### 5. **Bill of Materials (BOM) (`bom/` Folder)**
- Go to **Reports > Bill of Materials (BOM)**.
- Export as **CSV or XLS**.

### 6. **Images (`Images/` Folder)**
- Screenshots of schematic, PCB layout, and 3D views.

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   [git clone htps://github.com/DhavalKalathiya-Xenox/LiPo-Battery-Charger-PCB.git]
   ```
2. Open the Altium project files (`.SchDoc`, `.PcbDoc`).
3. Modify the design as needed.
4. Generate Gerber files and send them for PCB fabrication.

---

## 🛠 Future Improvements
- Adding a **Battery Protection Circuit**.
- Optimizing **charging efficiency**.
- Integrating a **voltage regulator** for extended applications.

---

## 📜 License
This project is licensed under the **[MIT License](LICENSE)**.

---

## 📩 Contact & Contributions
For questions or improvements, feel free to **open an issue** or submit a **pull request**.

🚀 Happy Designing!
=======
# LiPo-Battery-Charger-PCB
LiPo Battery Charger PCB designed in Altium Designer
>>>>>>> fd80c9f (Initial commit with project files)
