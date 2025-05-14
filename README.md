> ⚠️ **Note:** Due to GitHub's limited PDF preview support, the `Report.pdf` may not render in-browser. Please download the file and open it locally to view the full report.

# MicrowaveChannelSimulator_NYU-Wireless-Communications-Course-Project
This is Siqi Bai and Bingsheng Hua's course project for Wireless Communications by professor Sundeep Rangan. You can check the details in Report.pdf.
This repository presents a physics-based simulation framework for modeling indoor wireless propagation in the 1–10 GHz frequency range. Built in MATLAB, the project combines electromagnetic modeling and system-level analysis through a series of modular steps:

- **Multilayer wall reflection modeling** via transfer-matrix theory
- **2D ray tracing** using first- and second-order image sources
- **Knife-edge diffraction** for edge effects
- **Power-delay profile** and **delay spread** analysis
- **Path-loss exponent** estimation
- **Phased-array beamforming** gain simulation
- **3D spatial visualization** of beam paths and gain coverage

## Key Features

- Accurate modeling of layered dielectric wall reflections
- Frequency-sweep propagation analysis (1, 3, 5, 10 GHz)
- Spatial and temporal channel metric extraction
- Phased-array beamforming with directional gain control
- Visualization of power heatmaps, delay spreads, and gain patterns

## File Structure

📁 wireless_project.mlx # Main MATLAB Live Script (end-to-end implementation)
📄 Report.pdf # Full technical report (NYU EE course)
fig1-fig8 # Results by Matlab

## Requirements

- MATLAB R2022a or later
- Signal Processing Toolbox
- Communications Toolbox
- MATLAB Live Editor (for .mlx execution)

## Applications

- Indoor wireless system planning
- Link budget estimation in multipath environments
- Research on phased-array and beamforming design
- Educational tool for propagation and channel modeling

## Authors

- Siqi Bai, New York University, Tandon School of Engineering  
- Bingsheng Hua, New York University, Tandon School of Engineering  

## License

This project is released for academic and non-commercial use. Contact the authors for reuse in published or proprietary tools.

---

If you use or reference this work, please consider citing the accompanying report or acknowledging the repository.
