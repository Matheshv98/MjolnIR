# MjÖlnir

**MjÖlnir** is a streamlined tool for visualizing and analyzing any 2D dataset — without writing repetitive Python or MATLAB scripts. Designed to simplify workflows, it lets users inspect, process, and export results on the fly while keeping projects organized and reproducible. By reducing workflow complexity, data isn’t just seen — it’s better understood.

---

## 📌 Scope

While originally developed for **2D infrared (2DIR) spectroscopy**, MjÖlnir is built to adapt seamlessly to any two-dimensional dataset, including:

- Excitation–emission matrices (EEM)
- 2D fluorescence spectra
- 2D electronic spectra
- Any other X–Y–Z dataset in matrix form

---

## ⚙️ Core Analytical Features

### 🔍 Smart Peak Detection  
- **Laplacian-based algorithm** for identifying peaks, even in noisy data  
- Adjustable sensitivity for fine-tuned, precise localization  

### ✂️ Cross-Section Analysis  
- Extract and fit slices along both **pump** and **probe** axes  
- Overlay multiple slices for direct comparison  

### 📉 Automatic Baseline Correction  
- **Spline-based correction** for background artifact removal  
- Visual preview of correction to verify quality  

### 🖨️ Publication-Ready Output  
- One-click export in **vector formats** (PDF/SVG)  
- Customizable fonts, axis labels, color scales, and grid/tick options  
- Style outputs to match common journal guidelines  

---

## 📥 Data Import Format

To ensure consistent and unambiguous analysis, MjÖlnir requires 2D spectral data in a standardized matrix format:

- **First row:** Probe (X-axis) values  
- **First column:** Pump (Y-axis) values  
- **Remaining cells:** Z-data values aligned to these dimensions  

**File format requirements:**  
- Comma `,` as the column delimiter  
- Period `.` as the decimal separator (e.g., `1950.5`)  

This format prevents ambiguity across different data representations (e.g., Pump vs. Probe axes swaps) and regional settings.

---
