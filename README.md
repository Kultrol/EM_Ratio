# Electron Charge-to-Mass Ratio Experiment

This repository contains the Python script, data, and lab report for the Electron Charge-to-Mass Ratio experiment conducted by Kevin Medina and William Cardet under the supervision of Prof. Werner Boeglin at Florida International University, Department of Physics. The experiment aimed to determine the electron's charge-to-mass ratio (e/m) by observing electron motion in a magnetic field.

## Experiment Overview

The experiment was structured to derive the e/m ratio using the Lorentz force principle, with electrons subjected to both electric and magnetic fields to bend their paths. The setup included Helmholtz coils, a vacuum tube with an electron gun, and measurement instruments for assessing the electron beam's curvature.

## Repository Structure

- `main.ipynb`: Jupyter Notebook containing the Python script for data analysis.
- `data/`: Directory containing raw data files from the experiment.
- `EM_Ratio_Report.pdf`: Comprehensive lab report detailing the experiment, methodology, data analysis, and findings.
- `images/`: Directory containing figures and graphs generated from the experiment.

## Methodology

The methodology section of our lab manual, provided by Prof. Werner Boeglin, guided our experimental procedures and data analysis. The process involved selecting specific voltages for electron acceleration, adjusting the magnetic field via Helmholtz coils, and measuring the electron beam's radius of curvature to calculate the e/m ratio.

## Data Analysis

Data analysis was performed using a custom Python script, encapsulated within a class structure for modularity. The script facilitated data importation, cleaning, statistical analysis, and visualization, leading to the determination of the charge-to-mass ratio for electrons.

## Findings

Our findings, including the calculated e/m ratios at different voltages and their comparison with the accepted value, are detailed in the `EM_Ratio_Report.pdf`. Minor deviations observed are discussed within the context of experimental limitations and uncertainties.

## References

Refer to the `EM_Ratio_Report.pdf` document for a detailed list of references and citations used throughout our experiment and analysis.

## Acknowledgements

We extend our gratitude to Prof. Werner Boeglin for his guidance and the lab manual that significantly contributed to the experiment's success. Special thanks to the Department of Physics at Florida International University for providing the necessary facilities and equipment.

---

For more information or questions regarding this experiment, please contact [me](mailto:kmedi060@fiu.com).

---
## Description of Class Used in the Script

### `VoltageTrial` Class

The `VoltageTrial` class is central to the experiment's data processing. It represents a series of voltage trials within the physics experiment, focusing on varying coil radii. The class is designed to initialize with specific experiment parameters, including voltage, currents, path diameter, and path diameter uncertainty. It provides methods for calculating path radii uncertainty, magnetic fields, charge to mass ratio, and their uncertainties, and for plotting the results. This class streamlines the analysis from raw data to finalized graphs, illustrating the charge to mass ratio versus current for each trial.
