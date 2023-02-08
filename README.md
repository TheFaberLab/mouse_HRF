# Whole-brain mouse HRF
Whole-brain mouse hemodynamic response function (HRF) for GLM-based analysis of BOLD fMRI studies in mice.

# Overview
To detect reliable BOLD response of task fMRI measurements across the brain in mice, we have determined a whole-brain mouse HRF for analysis of BOLD fMRI studies. This HRF is based on 88 BOLD measurements in 30 animals and proceeds faster than the human HRF, which is implemented in the software SPM by default. The whole-brain mouse HRF provides improved detection performance of brain activation.

# Software Requirements
The script was written for implementation in SPM12 (https://www.fil.ion.ucl.ac.uk/spm/software/spm12/). 

# Implementation in SPM
Add the file spm_mouse_defaults.m to your MATLAB path and rename the file to spm_my_defaults.m. SPM will automatically look for this file and use the defaults specified in the file instead of those in the original defaults program.
The HRF parameters are loaded when the software SPM is opened.
