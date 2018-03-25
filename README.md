# NEURAL NETWORK - MACHINE LEARNING 

* Applied Neural Network Machine Learning to predict the gender of a voice using acoustic properties of the voice and speech.

## Voice Gender Recognition
Gender Recognition by Voice and Speech Analysis

This database was created to identify a voice as male or female, based upon acoustic properties of the voice and speech. The dataset consists of 3,168 recorded voice samples, collected from male and female speakers. The voice samples are pre-processed by acoustic analysis in R using the seewave and tuneR packages, with an analyzed frequency range of 0hz-280hz (human vocal range).

## The Dataset
The following acoustic properties of each voice are measured and included within the CSV:

* meanfreq: mean frequency (in kHz)
* sd: standard deviation of frequency
* median: median frequency (in kHz)
* Q25: first quantile (in kHz)
* Q75: third quantile (in kHz)
* IQR: interquantile range (in kHz)
* skew: skewness (see note in specprop description)
* kurt: kurtosis (see note in specprop description)
* sp.ent: spectral entropy
* sfm: spectral flatness
* mode: mode frequency
* centroid: frequency centroid (see specprop)
* peakf: peak frequency (frequency with highest energy)
* meanfun: average of fundamental frequency measured across acoustic signal
* minfun: minimum fundamental frequency measured across acoustic signal
* maxfun: maximum fundamental frequency measured across acoustic signal
* meandom: average of dominant frequency measured across acoustic signal
* mindom: minimum of dominant frequency measured across acoustic signal
* maxdom: maximum of dominant frequency measured across acoustic signal
* dfrange: range of dominant frequency measured across acoustic signal
* modindx: modulation index. Calculated as the accumulated absolute difference between adjacent measurements of fundamental frequencies divided by the frequency range
* label: male or female

## Read Data

* Coverted data into pandas data frame

## Data Pre-Preocessing 
* Splited data into test and training data
* Scaled the training and testing data
* Encoded the labels
* Converted the encoded labels into one-hot-encoding

## Create Deep Learning Model
* Created Machine Learning model
* Added hidden aand out put activation layers by using 'relu' and 'softmax' 
* Compiled the model
* Fit the model

## Quantify Trained Model
* Test the accuracy and Normal Neural Network Loss

## Predictions 
* Used the model to test the testing data to make predictions

## Conclusion 
* 20 observations converted into a data frame 
* With 98% of accuracy, voice recognition between male and female observed. 

## Tools Used 
* Pyton
* Pandas
* Numpy
* Sklearn
* Keras 
* Machine Learning tools 
* Neural Network tools 


