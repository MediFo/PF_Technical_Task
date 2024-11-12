Technical Task
Position: Energy Technologies Researcher (KTP)

Summary:
Develop a load flow simulation using OpenDss

Specifications:

Three-phase source: Two sources at 11 kV, 50 Hz, with no internal impedance.
Bus: Six buses, each with voltage measurement capability.
LV Load: Two low-voltage loads, connected downstream of transformers, set to any reasonable value.
HV Load: Two high-voltage loads, connected upstream of transformers, set to any reasonable value.
Transformer: Two transformers with a ratio of 11 kV to 0.4 kV, set to any reasonable rating and impedance, with power measurement.
RL Line: As many as necessary, with current measurement capability and impedance set to any reasonable value.
Switch: One switch to alter the low-voltage network topology configuration.

Task Description:

a. Create an electricity distribution network model as specified above

b. Run two load flow simulations: one with the switch open and one with the switch closed.

c. Export the bus voltages, line currents, and transformer power data in a tabular format.


Stretch Task (optional):

d. If time permits, consider extending the simulation with one or more of the following:

e. Apply a load profile to one or more loads.

f. Add a renewable generator, such as solar PV, to one of the low-voltage buses.

g. Assign x and y coordinates to network elements and display results in a single-line diagram or geospatial format.

h. Export the model in an interchange format, then import it into a different open-source tool


