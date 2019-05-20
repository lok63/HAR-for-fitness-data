# HAR-for-fitness-data
Human Activity Recognition for workout exercises

Re-produce the code in python for the study conducted in this paper [MyoGym - Introducing an Open Gym Data Set for Activity Recognition Collected Using Myo Armband](https://www.researchgate.net/publication/319603676_MyoGym_introducing_an_open_gym_data_set_for_activity_recognition_collected_using_myo_armband)

## TO-DO

- [ ] Subject Dependent evaluation
- [ ] Subject Independent evaluation

### 2. Feature Extraction
- [ ] Time domain [ Mean, std, variance, interquartile range (IQR), mean absolute deviation (MAD), correlation between axes, entropy Kurtosis ] 
- [ ] Fourier Transform, Wavelet Transform
- [ ] PCA, LDA, Autoregressive Model (AR) , HAAR filters

### 3. Time Window selection
- [ ] Windows [0.08s, 1, 1.5, 3, 5, 7, 12, 30]

### 3. Feature Selection
- [ ] (BIC) Bayessian Information Criterion   
- [ ] (MDL) Minimum Description Length 
- [ ] (CFS) Correlation-based Feature Selection 
- [ ] (MRMR) Minimum Redundancy Maximum Relevance 
  - [ ] Minimum mutual information between features
  - [ ] Maximal mutual information between the classes and the features



