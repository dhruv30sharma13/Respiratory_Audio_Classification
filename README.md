# Respiratory_Audio_Classification
Used ICPHI-2017 dataset to classify respiratory audio recordings to classify them on the presence of crackles and wheezles, which can be used by medical practitioners to diagnose respiratory diseases.

Ideas used:
  -Conversion audio files to spectrograms using librosa
  -Create CNN model to detect spatial features from spectrograms
  -Make prediction on basis of learned features for presence or absence of Crackle or Wheeze
  
Libraries/Frameworks:
  -Tensorflow -- to make the neural networks, do predictions.
  -Librosa -- to pre-process audio files
  -Numpy -- perform mathematical operations on image arrays
  -OpenCV -- to deal with images (here spectrograms) in python
  
Metrics obtained:
  -Accuracy -- 85.47% (test)
  -AUC score -- 0.76
