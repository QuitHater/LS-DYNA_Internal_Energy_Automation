# LS-DYNA Internal Energy Extractor 🚀

A simple **Python GUI tool** to extract and visualize **internal energy data** from **LS-DYNA binout files**.  

---

## ✨ Features
- 📂 Select LS-DYNA **binout file** and component IDs
- 📊 Generate **interactive Internal Energy vs Time plots**
- 🏆 Auto-detect and plot **Top 5 components with maximum internal energy**
- 💾 Export **HTML reports with built-in CSV download buttons**
- 📑 Save **summary CSV** with maximum energy values
- 🎯 Available as both:
  - ✅ **Standalone EXE** (no Python required)
  - ✅ **Compiled PYC** (for Python users)

---

## 📦 Installation Options

### Option 1: Use Standalone EXE (Recommended for non-Python users)
1. Download the zipped executable: Click here=> [`Plot_Internal_Energy_by_ids_LS-Dyna.zip`](https://drive.google.com/file/d/1zFb2f7jU6wtBwkF8fuemghOtc2tW1E9i/view?usp=sharing)
2. Extract and double-click `Plot_Internal_Energy_by_ids_LS-Dyna.exe`.

![Screenshot 2025-08-31 225442](https://github.com/user-attachments/assets/7eef0969-d961-494c-be26-b9cba211960f)

3. Start extracting and visualizing LS-DYNA data ✅

![First_Graph](https://github.com/user-attachments/assets/fa1c955d-3207-47bd-b267-88923a6ea07b)

_No Python required!_

---

### Option 2: Use Compiled PYC (For Python users)
1. Make sure you have Python **3.10+**
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the python file:
   ```bash
   python Plot_Internal_Energy_by_ids_LS-Dyna.pyc
