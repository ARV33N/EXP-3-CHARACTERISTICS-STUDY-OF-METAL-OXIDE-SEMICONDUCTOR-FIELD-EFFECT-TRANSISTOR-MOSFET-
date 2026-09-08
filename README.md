# EXP-3-CHARACTERISTICS-STUDY-OF-METAL-OXIDE-SEMICONDUCTOR-FIELD-EFFECT-TRANSISTOR-MOSFET-
# AIM
To simulate the drain and transfer characteristics of a MOSFET using LTspice software and to determine its drain resistance and transconductance.
# APPARATUS / SOFTWARE REQUIRED
•	PC/Laptop
•	LTspice simulation software
•	MOSFET device/model
•	DC voltage sources
•	Voltage/current probes
# THEORY
# 1. Transfer Characteristics
In MOSFET applications, the input signal is the gate-to-source voltage VGS and the output is the drain current ID. The ability of a MOSFET to amplify the signal is given by the output/input ratio called transconductance.

# 2. Transconductance:
gm = dID / dVGS    (with VDS kept constant)
The transfer characteristic represents the relationship between ID and VGS for a constant VDS.

# 3. Drain Characteristics
A MOSFET operates in three regions:
1.	Cut-off region
2.	Linear/Ohmic region
3.	Saturation region

# 4. Cut-off Region: The MOSFET is in cut-off when VGS < VT. The drain current is approximately zero.
Linear Region: The MOSFET operates in the linear region when VGS > VT and VDS < (VGS − VT).
Saturation Region: The MOSFET operates in saturation when VGS > VT and VDS ≥ (VGS − VT).
Drain resistance is obtained from the slope of the drain characteristic:
rd = dVDS / dID    (with VGS kept constant)

# PROCEDURE
# A. Transfer Characteristics
1.	Connect the MOSFET circuit as per the circuit diagram in LTspice.
2.	Set the required VGS and VDS values.
3.	Set the required DC sweep parameters and secondary values.
4.	Place the voltage/current probe at the required terminal of the MOSFET.
5.	Run the simulation.
6.	Observe and plot the relationship between ID and VGS.
7.	Determine the transconductance gm from the slope of the transfer characteristic.

# B. Drain Characteristics
1.	Connect the MOSFET circuit as per the circuit diagram in LTspice.
2.	Set the required VGS and VDS values.
3.	Set the required DC sweep parameters and secondary sweep values.
4.	Place the voltage/current probe at the required terminal of the MOSFET.
5.	Run the simulation.
6.	Observe and plot the relationship between ID and VDS for different values of VGS.
7.	Identify the cut-off, linear and saturation regions.
8.	Determine the drain resistance rd from the slope of the drain characteristic.
# OBSERVATION
# A. Transfer Characteristics
<img width="1097" height="676" alt="image" src="https://github.com/user-attachments/assets/5a54b137-fbcf-4d1c-84b8-9afea9d4b1fb" />

# B. Drain Characteristics
<img width="1107" height="588" alt="image" src="https://github.com/user-attachments/assets/4a3d42c8-3da2-4d43-b3c8-439db3b44627" />

# PRECAUTIONS
•	Check the MOSFET terminal connections before starting the simulation.
•	Use appropriate voltage sweep limits.
•	Keep VDS constant while obtaining transfer characteristics.
•	Keep VGS constant for each drain-characteristic curve.

# RESULT
Thus, the drain and transfer characteristics of the MOSFET were simulated using LTspice. 




