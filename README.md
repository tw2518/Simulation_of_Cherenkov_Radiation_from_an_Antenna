# Simulation_of_Cherenkov_Radiation_from_an_Antenna
Four waveforms of the A and J and their spectra.

This repository contains four different signals: sinusoidal, PM, AM and PM&AM.
The guideline is written in the code, but there are still two things to notice.

1. Clear all the variables every time after plotting a graph with a  function in class Fields before plotting another graph.
   If not, the console will return: "'list' object is not callable"
   This is because a 'list' object can only be called once outside the class.
   
2. To plot the A and J waves, the time range in S1 should be changed to 3e-8
   To plot the spectra, the time range in S1 should be changed to 3e-6
