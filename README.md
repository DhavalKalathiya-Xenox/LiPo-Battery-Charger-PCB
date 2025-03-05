# LiPo Battery Charger (Altium Design)

## Overview
This project is a **LiPo Battery Charger** designed using **Altium Designer**. The charger supports **3.7V LiPo cells** and provides charging at **500mA or 100mA**. It is designed for **single-cell Li-Ion or Li-Polymer batteries**.

![LiPo Battery Charger PCB](images/Lipo-Charger-3D.png)

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

## 📁 Project Structure
```
LiPo-Battery-Charger/
│── docs/               # Documentation files (PDFs, reports)
│── schematics/         # Altium schematic files (.SchDoc)
│── pcb/                # PCB layout files (.PcbDoc)
│── gerber/             # Gerber files for PCB fabrication
│── 3d_models/          # 3D model files (.step)
│── bom/                # Bill of Materials (.csv, .xls)
│── images/             # Screenshots of schematic, PCB, 3D views
│── README.md           # Project description (this file)
│── LICENSE             # (Optional) License for open-source use
```

---

## 🛠️ Required Files & How to Get Them
### 1. **Schematic Files (`schematics/` Folder)**
- Export **.SchDoc** from Altium Designer.

### 2. **PCB Layout Files (`pcb/` Folder)**
- Export **.PcbDoc** from Altium Designer.

### 3. **Gerber Files (`gerber/` Folder)**
- Go to **File > Fabrication Outputs > Gerber Files**.
- Select layers (Top, Bottom, Silkscreen, Solder Mask, Drill File).
- Click **Generate** & save.

### 4. **3D Model Files (`3d_models/` Folder)**
- Open **PcbDoc > File > Export > STEP 3D**.
- Save as `.step`.

### 5. **Bill of Materials (BOM) (`bom/` Folder)**
- Go to **Reports > Bill of Materials (BOM)**.
- Export as **CSV or XLS**.

### 6. **Project Documentation (`docs/` Folder)**
- Contains reports, circuit explanations, and fabrication drawings.

### 7. **Images (`images/` Folder)**
- Screenshots of schematic, PCB layout, and 3D views.

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/LiPo-Battery-Charger.git
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
