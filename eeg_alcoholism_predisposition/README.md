# EEG Data Analysis Project

This project aims to study the predisposition to alcoholism in different individuals by analyzing EEG (Electroencephalography) data collected from two study groups: an alcoholic group and a control group. EEG data provides insights into the electrical activity of the brain and can be used to understand brain functioning and patterns.

## Project Overview

The main objective of this project is to analyze the EEG data collected from individuals in order to identify potential differences or patterns between the alcoholic group and the control group. By comparing the EEG signals between these two groups, we aim to gain insights into the potential indicators or suseptibility to alcoholism.

## Data Collection

The EEG data is accessed via an open source repository on [kaggle.com](kaggle.com). A link to the data files is provided on top of the jupyter notebook. The data was collected using electrodes placed on the scalp of participants from both groups. The data collection process involved recording brain signals while participants were exposed to a set of three independent visual stimuli: S1 obj, S2 match, and S2 nonmatch. Data are characterized by the following attributes:

Each trial is stored in its own file and will appear in the following format.

trial number sensor position sample num sensor value subject identifier matching condition channel name time

0 FP1 0 -8.921 a S1 obj 0 co2a0000364 0

0 AF8 87 4.14 a S1 obj 33 co2a0000364 0.33

The columns of data are:

the trial number,

sensor position,

sample number (0-255),

sensor value (in micro volts),

subject identifier(Alcoholic(a) or Control (c)),

matching condition(a single object shown (S1 obj), object 2 shown in a matching condition (S2 match), and object 2 shown in non matching condition (S2 nomatch)),

channel number(0-63),

name(a serial code assigned to each subject),

time(inverse of sample num measured in seconds)) 

## Data Analysis

The project involves several steps of data analysis, which may include:

1. Preprocessing: Cleaning and filtering the raw EEG data to remove artifacts, noise, and unwanted signals.
2. Feature Extraction: Extracting relevant features from the preprocessed EEG data that can capture important characteristics or patterns.
3. Data visualization: Plotting interactive figures that can visualize the trends in data in terms of a number of features.
4. Statistical Analysis: Conducting statistical analysis, such as calculating collective properties in data or correlation analysis, to identify significant differences or relationships between the two groups.
4. Machine Learning Models: Developing machine learning models to classify individuals into the alcoholic and control groups based on the EEG features extracted (under develpment).
5. Interpretation: Interpreting the results, visualizing the findings, and presenting meaningful insights from the data analysis process.

## Directory Contents

- `notebooks`: This includes Jupyter notebooks used for data preprocessing, feature extraction, statistical analysis, and machine learning modeling.
- `images/`: This directory includes the images that are used in the notebook as well as some additional plots.
- `README.md`: The current file, providing an overview of the project.

## Acknowledgement

This project is created under the joint collaboration of __Alireza Shakerpoor__ and __Aref Hashemi__.

Feel free to contribute, open issues, or suggest improvements. We hope this project contributes to the understanding of alcoholism predisposition through EEG data analysis.
