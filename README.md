# Emotion classification using electroencephalography statistical features

# Project Overview
The main goal is create an exploration and classifier of motor imagery commands from EEG signals. Dataset taken from Berlin Brain-Computer Interface.

## Exploratory Data Analysis
Follow the notebook : `notebook/EEG Classification.ipynb` section Exploratory data analysis
# Installation and Setup
Install requirements.txt 


# Data
## Source Data
Please check https://www.bbci.de/competition/iv/
This Analysis is based on Data sets 2a: ‹4-class motor imagery›.
[22 EEG channels (0.5-100Hz; notch filtered), 3 EOG channels, 250Hz sampling rate, 4 classes, 9 subjects]

This data set consists of EEG data from 9 subjects.

The cue-based BCI paradigm consisted of four different motor imagery tasks, namely the imagination of movement of the left hand (class 1), right hand (class 2), both feet (class 3), and tongue (class 4).

Two sessions on different days were recorded for each subject. Each session is comprised of 6 runs separated by short breaks. One run consists of 48 trials (12 for each of the four possible classes), yielding a total of 288 trials per session.

Data in the repo is missing because of the size
# Code structure

```bash
└───EEG_BCI_Competition
    ├───notebook
        └───EEG_Classification.ipynb
    ├───data
    └───References
```

Please Follow the notebook to understand the analysis the of the data and the model.


# Acknowledgments/References
- Jose Garcia
# License
MIT
