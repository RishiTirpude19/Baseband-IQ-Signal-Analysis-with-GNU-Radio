# GNU Radio-Based 8-QAM Signal Analysis

## 📌 Overview
This project demonstrates the analysis and demodulation of an **unknown IQ baseband signal** using **GNU Radio Companion (GRC)**.  
The objective was to estimate key signal parameters, perform synchronization, and identify the correct modulation scheme.

---

## 🔬 Key Features
- Processed an IQ signal sampled at **512 kHz**.  
- Estimated a **symbol rate of 300 kHz** with approximately **3 samples per symbol**.  
- Determined a **zero carrier frequency offset** through spectral analysis.  
- Applied synchronization and carrier recovery techniques to stabilize the constellation.  
- Confirmed the modulation scheme as **8-QAM** using constellation visualization.  

---

## 🛠️ Tools & Technologies
- **GNU Radio Companion (GRC)**  
- **Signal Processing Blocks**: FFT, Mth-power method, Costas Loop, Symbol Sync  
- **Python (for flowgraph support)**  

---

## 📈 Workflow
1. **Spectral Analysis**: Observed FFT of the IQ data to estimate symbol rate and carrier offset.  
2. **Synchronization**: Applied symbol timing recovery and carrier recovery for accurate demodulation.  
3. **Constellation Recovery**: Visualized constellation diagram to validate symbol mapping.  
4. **Modulation Detection**: Identified the signal modulation as **8-QAM**.  

---

## 📂 Project Structure
- `gnu_assignment.grc` → GNU Radio Companion flowgraph.  
- `gnu_assignment.pptx` → Presentation report summarizing methodology and results.  
- `README.md` → Project documentation (this file).  

---

## 🚀 Results
- Successfully recovered and demodulated an unknown IQ signal.  
- Verified **8-QAM modulation scheme** with accurate symbol reconstruction.  
- Developed a reproducible flowgraph that can be adapted for other digital modulation formats.  

---

## 📌 Authors
- **Rishi Tirpude** – B.Tech, Electronics and Communication Engineering, IIT Guwahati  

---
