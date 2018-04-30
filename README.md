# TDIChallenge2018

This is part of the submission for the The DataIncubator Challenge 2018

Every year, thousands of ECG records are being generated around the world in hospitals and medical facilities. These ECG records might indicate a cardiac pathology that might need an immediate medical response. Yet, only very limited number of medical professionals can interpret and understand this signal. Here I suggest, a machine learning technique, to automatically interpret this signal. In particular, I use a pre-trained deep net, to classify for the most common cardiac arrhythmia called Atrial Fibrillation.   

To perform this analysis, I used 8528 single lead ECG records that were published as part of the 2017 physionet challenge. All records were given as a time series, and were converted to a human readable image using API provided by physionet. 

These images were used to train a convolutional deep network, with an accuracy of about 80% (almost as good as a cardiologist level).

Files included:
1. TDIChallenge2018.ipynb - the script used to generate this result 
2. confusion_matrix.png - the resulting confustion matrix of the analysis
3. normal_rhythm.jpg - an example of the algorithm input - a normal ECG record
