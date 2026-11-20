# Plotting-MMM-Distance-Distributions
A Python script for plotting and comparing distance distributions obtained from MMM simulations.

**Features**
Supports any number of MMM distance distribution datasets.
Plots multiple distance distributions in a single figure.
Normalizes all distributions to the highest peak across all datasets.
Exports figures in high-resolution PNG (600 dpi) and vector-based PDF formats.

**Requirements**
Python
NumPy
Matplotlib

**Input Data**
The script requires MMM distance distribution files (distr.dat) containing at least two columns: Distance, r (nm); Probability, P(r)
Input data files are not included in this repository. Users should provide their own MMM simulation data.

**Usage**
Download this repository.
Open MMM_distance_plot.
Specify the paths to output folder and your MMM distribution files.
Assign legend labels to each dataset.
Set the figure filename.

**License**

This project is licensed under the MIT License. See the LICENSE file for details.

**Author**
Alexey Chubarov
https://github.com/chubarov-lab
