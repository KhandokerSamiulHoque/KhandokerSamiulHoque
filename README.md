### Hi, I'm Samiul

I'm a Power Electronics Engineer at RETC (Renewable Energy Test Center) in Fremont, California, since July 2025. I run UL 1741 inverter performance and safety tests and lead PV module qualification testing aligned with IEC certification sequences. That includes I-V curve tracing, temperature coefficients, insulation resistance, wet leakage and dielectric withstand. I also supported an OSHA/NRTL witness audit by executing UL 1741 inverter tests.

On my own time I build machine learning tools for problems I see in the lab: finding defects in electroluminescence images, estimating PV output from weather, catching faults in grid-connected inverters, and checking whether a model's accuracy survives an honest evaluation. All of this research uses public data or my own thesis data, never employer data.

I hold an M.S. in Electrical Engineering from San Francisco Bay University (2024, GPA 3.76) and a B.Sc. in Electrical and Electronic Engineering from BRAC University (2021). I'm applying to PhD programs for Fall 2027 in ML for photovoltaics and power electronics.

#### Research code
Every repository states its limits and has been rerun from scratch to match its reported numbers.

| Repository | What it does | Status |
|---|---|---|
| [pv-el-defect-screening](https://github.com/KhandokerSamiulHoque/pv-el-defect-screening) | Interpretable defect screening on 2,624 ELPV solar-cell images. F1 0.670 on any defect, ROC-AUC 0.816 on high-confidence defects | Published, IJSRA 2026 ([DOI](https://doi.org/10.30574/ijsra.2026.20.2.1601)) |
| [pv-el-acquisition-shift](https://github.com/KhandokerSamiulHoque/pv-el-acquisition-shift) | The same screening model under exposure, contrast, noise and blur shifts. Underexposure leaves F1 flat but doubles calibration error | In preparation |
| [gpvs-fault-detection](https://github.com/KhandokerSamiulHoque/gpvs-fault-detection) | Fault classification on GPVS-Faults (grid-connected PV inverter, 7 fault types). Near-perfect F1 under random splits drops to 0.15 to 0.52 when the model must transfer between MPPT and IPPT modes | In preparation |
| [pv-current-estimation](https://github.com/KhandokerSamiulHoque/pv-current-estimation) | Short-circuit current from weather for clean vs. dusty modules. Random forest R² 0.847 on held-out days; dust cuts midday current by 4% to 22% depending on the month | In preparation |
| [inverter-efficiency-ml](https://github.com/KhandokerSamiulHoque/inverter-efficiency-ml) | Inverter efficiency from the CEC database with a target-leakage audit. F1 falls from 0.9994 to 0.9736 once the leak is removed | In preparation |
| [federated-energy-ids](https://github.com/KhandokerSamiulHoque/federated-energy-ids) | Federated intrusion detection across 10 simulated sites. Under a poisoning attack, coordinate median holds 0.757 accuracy against 0.251 for FedAvg | In preparation |

#### Selected publications
- K. Hoque, "Interpretable Machine Learning for Photovoltaic Defect Screening: A Reproducible Electroluminescence Benchmark," *IJSRA*, 2026 (sole author). [doi:10.30574/ijsra.2026.20.2.1601](https://doi.org/10.30574/ijsra.2026.20.2.1601)
- "Integration of IoT in Energy Sector," *IJCA* 186(36), 2024. [link](https://www.ijcaonline.org/archives/volume186/number36/integration-of-iot-in-energy-sector/)
- "Performance Analysis of Yagi and Helix Antennas at 7.2 GHz with Far-Field Propagation Evaluation," IEEE conference, 2025. [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/11013571)
- "Hepatitis C Prediction Applying Different ML Classification Algorithm," Springer LNNS, 2025. [doi:10.1007/978-981-96-3250-3_32](https://doi.org/10.1007/978-981-96-3250-3_32)
- "Feature-Driven Supervised Learning for Detecting DDoS Attack," *IJSRA*, 2021. [doi:10.30574/ijsra.2021.4.1.0204](https://doi.org/10.30574/ijsra.2021.4.1.0204)

Full list on [Google Scholar](https://scholar.google.com/citations?user=8e4lHfUAAAAJ).

#### Earlier projects
- [AI-Based-Traffic-Management-System](https://github.com/KhandokerSamiulHoque/AI-Based-Traffic-Management-System): YOLOv8 vehicle detection for adaptive traffic signal timing (MSEE capstone, 2024)
- [pv-module-weather-analysis](https://github.com/KhandokerSamiulHoque/pv-module-weather-analysis): my BSc thesis, neural-network models of output for clean vs. dusty PV modules (2021)
- [sfbu-msee-coursework](https://github.com/KhandokerSamiulHoque/sfbu-msee-coursework): Digital Design and HDL (SystemVerilog), Computer Architecture (MIPS) and Embedded Engineering (Raspberry Pi) labs

#### Skills
- **ML and data:** Python, NumPy, pandas, scikit-learn, LightGBM, Keras, YOLOv8, Matplotlib
- **Engineering:** MATLAB/Simulink, SystemVerilog/Verilog, C/C++, Raspberry Pi, AutoCAD
- **Test and lab:** UL 1741 inverter testing, IEC PV module qualification, grid simulators, DC sources, power analyzers, DAQ, I-V tracers
- **Software testing:** Selenium WebDriver, Java, TestNG

#### Contact
[Google Scholar](https://scholar.google.com/citations?user=8e4lHfUAAAAJ) · [ORCID 0009-0008-0756-2395](https://orcid.org/0009-0008-0756-2395) · [LinkedIn](https://linkedin.com/in/khandoker-samiul-hoque-b54a7814b) · khandoker.hoque@outlook.com
