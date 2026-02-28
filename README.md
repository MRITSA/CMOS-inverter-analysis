# CMOS-inverter-analysis
Designed and simulated a CMOS inverter to analyze Voltage Transfer Characteristics (VTC), noise margins, propagation delay, and dynamic behavior. Studied the impact of transistor sizing (W/L ratio) on switching performance using DC sweep and transient analysis.

## Tools & Technology
- OrCAD PSpice A/D
- CMOS MOSFET Models
- DC Sweep Analysis
- Transient Analysis

##  Circuit Configuration
Supply Voltage:
VDD = 5V  

Transistor Parameters:
NMOS → W = 1µm, L = 0.18µm  
PMOS → W = 2µm, L = 0.18µm  

PMOS width is chosen larger to compensate for lower hole mobility and achieve near-symmetric switching.

## Simulation Analysis

# 1️ Voltage Transfer Characteristics (VTC)
- Performed DC sweep of input from 0V to 5V
- Plotted Vout vs Vin
- Extracted switching threshold voltage (VM)
- Observed S-shaped characteristic due to nonlinear MOS behavior

# 2️ Noise Margin Estimation
- Determined VOH, VOL, VIH, and VIL from VTC
- Calculated NMH and NML

# 3️ Transient Analysis
- Applied pulse input
- Measured:
  - tPHL (High-to-Low delay)
  - tPLH (Low-to-High delay)
- Calculated average propagation delay
