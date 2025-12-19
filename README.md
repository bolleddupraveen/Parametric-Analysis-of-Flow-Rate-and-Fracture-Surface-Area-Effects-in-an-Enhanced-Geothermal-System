# Parametric-Analysis-of-Flow-Rate-and-Fracture-Surface-Area-Effects-in-an-Enhanced-Geothermal-System 
# Project Description

In this project, I developed and analyzed an Enhanced Geothermal System (EGS) model to study the effect of circulation flow rate and effective fracture surface area on:

Net electrical power output

Produced geofluid temperature

Thermal drawdown behavior

Long-term sustainability of electricity generation

The study focuses on electricity-only generation using a subcritical Organic Rankine Cycle (ORC) and is intended as a screening-level feasibility analysis for EGS development.

# System Configuration Used

Well configuration: Deviated wells

Injection wells: 2

Production wells: 2

Reservoir depth: 3000 m

Working fluid: Water

End-use option: Electricity only

Power plant: Subcritical ORC

Note:
The specified flow rates represent the flow rate per production well.
Since two production wells are used, the total circulation flow rate is twice the per-well value.

## Simulation Cases Performed
# Flow Rate Sensitivity Analysis

In this analysis, I kept the effective fracture surface area constant at 250,000 m² and varied the circulation flow rate.

Flow rate per production well:

20 kg/s → 40 kg/s total

30 kg/s → 60 kg/s total

40 kg/s → 80 kg/s total

50 kg/s → 100 kg/s total

This study highlights the trade-off between higher initial power output and long-term system sustainability.

# Fracture Surface Area Sensitivity Analysis

In this analysis, I fixed the circulation flow rate at 20 kg/s per production well and varied the effective fracture surface area to represent different stimulation intensities.

Fracture surface areas studied:

100,000 m²

200,000 m²

300,000 m²

This analysis demonstrates the role of fracture surface area in controlling heat exchange efficiency and thermal drawdown.

# Key Findings

Increasing circulation flow rate increases early-time net electrical power, but:

Significantly increases pumping power

Accelerates thermal drawdown

Reduces the economic lifetime of electricity-only operation

Lower flow rates:

Reduce pumping losses

Maintain positive net power for longer durations

Improve long-term sustainability

Larger fracture surface areas:

Improve heat-transfer efficiency

Reduce thermal decline

Extend electricity-generation viability

Overall, I found that moderate flow rates combined with sufficient fracture surface area provide the best balance between power output and sustainability.

# Repository Structure
.
├── Report/
│   ├── Final_Report.pdf
│   └── LaTeX_Source/
│       └── EGS_Report.tex
│
├── Data/
│   ├── EGS_FlowRate & Fracture area_Cases.xlsx
│   
│
├── Figures/
│   ├── Net_Power_FlowRate.png
│   ├── Temperature_FlowRate.png
│   ├── Net_Power_FractureArea.png
│   └── Temperature_FractureArea.png
│
└── README.md

# Documentation

The final technical report is provided as a PDF

LaTeX source files are included for transparency

Excel files contain year-wise simulation input and output data

# Assumptions and Limitations

Fractures are represented using an effective surface area approach

Thermo-hydro-mechanical coupling is not explicitly modeled

Rock and fluid properties are assumed constant

Results are intended for screening-level analysis, not field-scale design

# Scope for Future Work

Coupled thermo-hydro-mechanical (THM) modeling

Explicit discrete fracture network representation

Evaluation of combined heat and power (CHP) operation

Economic optimization and uncertainty analysis

# Author

Praveen Vinny Prakash
B.Tech – Petroleum Engineering
Final Year Project

📜 License

This project is shared for academic and learning purposes.
