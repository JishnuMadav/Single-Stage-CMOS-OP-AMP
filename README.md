# Single-Stage CMOS Operational Amplifier (180nm TSMC) – LTspice Simulation

##  Project Overview
This project involves the design and simulation of a **single-stage CMOS operational amplifier** using **180nm TSMC CMOS technology**, implemented in **LTspice**. The focus is on achieving proper transistor biasing, analyzing small-signal gain, and evaluating frequency response.

---

##  Features

- **Technology**: 180nm TSMC CMOS
- **Simulation Tool**: LTspice
- **Topology**: Single-stage differential amplifier with active current mirror load
- **Supply Voltage**: 3.3V
- **Design Focus**:
  - Proper MOSFET biasing (saturation region)
  - Mid-band gain tuning via W/L optimization
  - Frequency response and gain-bandwidth analysis
  - AC, DC, and transient analysis

---

##  Simulation Results

[Gain vs Frequency] 
<img width="1915" height="849" alt="image" src="https://github.com/user-attachments/assets/44eee902-b1e9-45c8-80f8-0a0fc46d0f57" />

--

##  How to Run the Simulation

1. **Download and install LTspice** (free from Analog Devices)
2. Open `draft4.asc` in LTspice
4. Ensure the `180nm_models.txt` is included using a `.include` SPICE directive
5. Run:
   - **DC operating point** to verify MOSFET biasing
   - **AC analysis** to extract gain and bandwidth
   - **Transient simulation** to observe time-domain response

---

## Author

**Jishnu Madav**  
_NITK Surathkal | Analog & Digital Enthusiast_  
