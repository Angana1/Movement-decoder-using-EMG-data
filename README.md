# 🧠 EMG Signal Analysis to Predict Finger Joint Movements
## Neural Signals and Signal Processing - Course Project (Autumn 2025)

##  Abstract

This project investigates EMG signal analysis for movement decoding using classification and regression approaches. In Part One, 12 finger movement classes from a single NinaPro subject were classified. After verifying that signals were already rectified and filtered, time- and frequency-domain features (e.g., RMS, MAV, WL, SSC, WAMP, VAR, IEMG, PSD) were extracted. An SVM classifier with hyperparameter tuning achieved high within-subject performance (validation accuracy 0.96, test 0.83). Feature selection using RFE, PCA, and mutual information showed that dimensionality could be reduced with minimal performance loss.
In Part Two, cross-subject generalization was evaluated using leave-one-subject-out validation across 27 subjects. Accuracy dropped significantly (mean 0.44), highlighting inter-subject variability, though performance improved with larger training sets.
Part Three addressed regression of joint angles using sliding windows, feature extraction, correlation-based reduction, and SVR modeling (Support Vector Regressor). The optimal RBF-SVR achieved strong predictive performance (test R² = 0.70).

## Applications

- Prosthetic hand control  
- Rehabilitation engineering  
- Gesture recognition systems  
- Human-computer interaction  
