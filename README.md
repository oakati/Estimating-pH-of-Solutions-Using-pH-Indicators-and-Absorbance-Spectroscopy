# Estimating-pH-of-Solutions-Using-pH-Indicators-and-Absorbance-Spectroscopy
This repo contains code and resources for estimating pH of solutions via pH indicators and absorbance spectroscopy. Solutions are mixed with indicators, resulting in measured absorbance spectra. If absorbance measurements of 3 distinct solutions with known pH are provided for calibration, the absorbance spectrum of a solution of unknown pH becomes sufficient for pH determination.

# Explanation of the .csv file
This program utilizes an input file in the form of a .csv file containing absorbance spectroscopy data for various solutions with known pH values. The file should contain data from four separate measurements. Two measurements should be performed for solutions at the limit values of the pH range for the indicator being used. For example, if using phenol red, measurements should be taken at pH 6 and 8, as phenol red measures pH values within the range of 6 to 8. The third measurement, used for calibration, can be taken at any pH within that range. The last two columns of the input file should contain the absorbance spectrum of the solution whose pH value is to be estimated. A sample input file is provided for reference.

# A remark on the estimation method
Typically, pH indicators primarily respond at two wavelengths, and the estimation method also uses those wavelengths. However, this program utilizes all combinations of wavelengths, and the final estimate is determined by taking the average of these measurements.

# Reference to the estimation method
https://chemlab.truman.edu/files/2015/07/pka1.pdf
