Measure the quadrature coherence scale on Borealis

Source code for generating and analyzing data from Xanadu's Borealis machine for initializing squeezed-vacuum states and thermal states, interfering them, then and measuring their quadrature coherence scales (QCSs) with photon number resolving detectors.

The files "Simulation_QCS_SV.ipynb" and "Simulation_QCS_Thermal.ipynb" can be used to inspect the circuit for generating various states and measuring their QCSs, using various values of noise or not as one desires.

The ipynb files beginning with "Execution" are used to run the program for various average numbers of photons on the remote device, then save the data.

The data are stored in the csv files, labelled by whether the state being measured was squeezed vacuum (SV) or thermal light (Th) and by the squeezing parameter r used to generate different average numbers of photons.

The data are analyzed and plotted in "Plot_QCS.ipynb."

The certificate.out file records the calibration data obtained from Borealis on the date that the experiment was conducted.

