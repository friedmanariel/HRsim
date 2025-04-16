# HRsim

HRsim is a specialized software designed for analyzing and comparing Fast-Transient AC Voltammetry (FTacV) experimental data with simulated data. The simulated data is generated using MECsim.
HRsim facilitates efficient scanning and parameter estimation by iterating over selected variables using the least squares method, minimizing the objective function S:
S=1/H×∑_(h=1)^H▒√((∑_(i=1)^N▒〖(f^exp (x_i )-f^sim (x_i))〗^2 )/(∑_(i=1)^N▒〖f^exp (x_i )^2 〗))

This optimization ensures the best fit between experimental and simulated data. The software calculates the current envelope of selected harmonics and compares it to the simulated data. With an intuitive interface and powerful computational capabilities, HRsim offers researchers a streamlined approach to refining electrochemical models and deriving valuable insights from FTacV measurements.
