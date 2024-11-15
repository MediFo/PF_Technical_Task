**Technical Task**
Position: Energy Technologies Researcher (KTP)

**Summary:**
Developing a load flow simulation using OpenDss

//**************************************//

Please run **PF_SnapMode.dss** for tasks (a) to (c).

For tasks (d) and (e), please run **PF_TimeSeriesMode.dss** (developed for time-series analysis to model load and PV profiles).

For tasks (f) and (g), please run **KTP_OpenDSS_Python.ipynb** (this script interacts with Python to execute PF_SnapMode.dss).

The **report** are available in the Excel file located in the **result** folder, with additional details provided in its subfolders.

//**************************************//

**Specifications:**

Three-phase source: Two sources at 11 kV, 50 Hz, with no internal impedance.
Bus: Six buses, each with voltage measurement capability.
LV Load: Two low-voltage loads, connected downstream of transformers, set to any reasonable value.
HV Load: Two high-voltage loads, connected upstream of transformers, set to any reasonable value.
Transformer: Two transformers with a ratio of 11 kV to 0.4 kV, set to any reasonable rating and impedance, with power measurement.
RL Line: As many as necessary, with current measurement capability and impedance set to any reasonable value.
Switch: One switch to alter the low-voltage network topology configuration.

**Task Description:**

a. Create an electricity distribution network model as specified above

b. Run two load flow simulations: one with the switch open and one with the switch closed.

c. Export the bus voltages, line currents, and transformer power data in a tabular format.


**Stretch Task (optional):**

If time permits, consider extending the simulation with one or more of the following:

d. Apply a load profile to one or more loads.

e. Add a renewable generator, such as solar PV, to one of the low-voltage buses.

f. Assign x and y coordinates to network elements and display results in a single-line diagram or geospatial format.

g. Export the model in an interchange format, then import it into a different open-source tool


