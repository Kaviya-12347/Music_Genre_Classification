# Music_Genre_Classification
A music genre classification system based on the k-Nearest Neighbors (KNN) algorithm, utilizing the widely-used GTZAN dataset. The key feature set used for classification is the Mel-frequency cepstral coefficients (MFCCs), which have proven effective in capturing the timbral characteristics of audio signals.

In this work, MFCC features were extracted from the audio samples, and the KNN algorithm was applied to classify the tracks into one of ten music genres. A custom distance metric was developed, taking into account the covariance and mean of the MFCC features to compute distances between feature vectors. The dataset was split into training and test sets with a 68% to 32% ratio. No additional preprocessing, such as normalization or noise reduction, was applied to the dataset.

The classifier achieved an accuracy of 68%, demonstrating the effectiveness of MFCC features in music genre classification. 
