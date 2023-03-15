# Electrocardiogram Prediciton
An electrocardiogram is a simple, painless test that measures your heart’s electrical activity. It’s also known as an ECG or EKG. Every heartbeat is triggered by an electrical signal that starts at the top of your heart and travels to the bottom. Heart problems often affect the heart’s electrical activity. An EKG records a picture of your heart’s electrical activity while you’re being monitored. The essence of the source code here is to predict the respective class of electrocardiogram. The dataset contains five classes of electrocardiogram signals. The five classes encompass:
i.	0 - “N” for normal heartbeats
ii.	1 - “S” for supra-ventricular premature
iii.	2 - “V” for ventricular escape
iv.	3 - “F” for the fusion of ventricular and normal
v.	4 - “Q” for unclassified heartbeats



# Dataset Used
[MIT-BIH Arrhythmia Database] (https://physionet.org/content/mitdb/1.0.0/)
## About MIT-BIH Arrhythmia Database
The MIT-BIH Arrhythmia Database contains 48 half-hour excerpts of two-channel ambulatory ECG recordings, obtained from 47 subjects studied by the BIH Arrhythmia Laboratory between 1975 and 1979. Twenty-three recordings were chosen at random from a set of 4000 24-hour ambulatory ECG recordings collected from a mixed population of inpatients (about 60%) and outpatients (about 40%) at Boston's Beth Israel Hospital; the remaining 25 recordings were selected from the same set to include less common but clinically significant arrhythmias that would not be well-represented in a small random sample.

The recordings were digitized at 360 samples per second per channel with 11-bit resolution over a 10 mV range. Two or more cardiologists independently annotated each record; disagreements were resolved to obtain the computer-readable reference annotations for each beat (approximately 110,000 annotations in all) included with the database.

This directory contains the entire MIT-BIH Arrhythmia Database. About half (25 of 48 complete records, and reference annotation files for all 48 records) of this database has been freely available here since PhysioNet's inception in September 1999. The 23 remaining signal files, which had been available only on the MIT-BIH Arrhythmia Database CD-ROM, were posted here in February 2005.


# Machine learning Model used
1. Logistic Regression
2. Support Vector Machine
3. Random Forest

# Installation
```
# windows users
pip install numpy pandas matplotlib
```
```
# Linux/Mac users
pip3 install numpy pandas matplotlib
```

# Requirement
1. Anaconda Enviroment
2. SKlearn API
3. Tensorflow API
