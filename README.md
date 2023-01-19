# Estimating-pH-of-Solutions-Using-pH-Indicators-and-Absorbance-Spectroscopy
This repo contains code and resources for estimating pH of solutions via pH indicators and absorbance spectroscopy. Solutions are mixed with indicators, resulting in measured absorbance spectra. Using 2 relative absorbance calculations and 1 calibration measurement, the unknown pH of a solution can be determined.

# Explanation of the .csv file
This program utilizes an input file in the form of a .csv file containing absorbance spectroscopy data for various solutions with known pH values. The file should contain data from four separate measurements. Two measurements should be performed for solutions at the limit values of the pH range for the indicator being used. For example, if using phenol red, measurements should be taken at pH 6 and 8, as phenol red measures pH values within the range of 6 to 8. The third measurement, used for calibration, can be taken at any pH within that range. The last two columns of the input file should contain the absorbance spectrum of the solution whose pH value is to be estimated. A sample input file is provided for reference.

# Reference to the estimation method
https://chemlab.truman.edu/files/2015/07/pka1.pdf
