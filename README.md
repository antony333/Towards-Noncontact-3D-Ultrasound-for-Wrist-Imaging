# Towards Noncontact 3DUltrasound for Wrist Imaging

Repository to share the MATLAB implementation of ultrasound 3D reconstruction from the ultrasound images and the orientation data collected

DATE 15-08-2023 : VERSION 1.0

## Authors
Antony Jerald, Madhavanunni A. N., Gayathri Malamal and Mahesh Raveendranatha Panicker
Center for Computational Imaging, Indian Institute of Technology Palakkad, Kerala, India.

## Instructions for the execution of codes
Please follow the below instructions to run the code.

Download the source code (.p file) and Demo files from the below google drive link
https://drive.google.com/drive/folders/1Tki-1H_kJP2GErW7ZMFKwdzOMczMqDQX?usp=sharing


Please note that the source code has the following dependencies:
(a) MUST Toolbox (ver.2.0): used for robust smoothing and vector flow visualisation
(b) Time-Frequency Toolbox (tftb-ver.0.2): used to obtain localised time-frequency plots of the beamformed signal
(c) The show_Figure6.m uses tiledlayout and requires MATLAB 2019b or higher for its execution
Download the MUST toolbox, Time-Frequency Toolbox and place it in source_code/lib/
Set appropriate values for bfParams.beamApod and bfParams.DMAS in mainCode_expPWIdisc.m and run the same. Please ensure that the paths provided in mainCode_expPWIdisc.m is valid.
The show_Figure3.m should be executed only after executing mainCode_expPWIdisc.m with saveEnable set to 1.
