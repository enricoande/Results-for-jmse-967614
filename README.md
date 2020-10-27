# Results-for-jmse-967614
This repository contains the data files for the results of the deep reinforcement learning algorithm for the control of a wave energy converter.

The aim of the files is to verify your results against those obtained with the method presented in the following article for reproducibility:
E Anderlini, S Hussain, GG Parker, M Abusara, and G Thomas, "Towards Real-Time Reinforcement Learning Control of a Wave Energy Converter", Journal of Marine Science and Engineering, 2020. 

The files are in .csv format. 

In the file name, it is possible to read the significant wave height in metres and the modal/peak wave energy period in seconds.

Each time series file the following columns:
1. Time [s],
2. Wave elevation [m],
3. Wave vertical velocity [m/s],
4. Buoy heave displacement [m],
5. Buoy heave velocity [m/s],
6. Wave excitation (incident & diffraction, or dynamic Froude-Krylov & scattering) force [N],
7. PTO force [N].
