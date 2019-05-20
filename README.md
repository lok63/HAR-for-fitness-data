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

* Having short windows might enchance the FE performance but it could increase the complexity of the system since the number of windows will be increased. 
* Really small windows might not be able to capture sufficient information to fully describe the performed activity
* Large windows could capture multiple activities 
* We can use overlapping windows to identify the transition period

- [ ] Windows [0.08s, 1, 1.5, 3, 5, 7, 12, 30]

### 3. Feature Selection

Feature selection is ideal for HAR systems which have many features such as HR monitors, temperatures sensors, humitity etc. In this case since we are using Accelerometers and Electormagnetic sensors we might avoid this tecnique initially. At the end of this project some of these methods will be implemented to test if they improve the performance of the current model

- [ ] <del>(BIC) Bayessian Information Criterion   
- [ ] <del>(MDL) Minimum Description Length 
- [ ] <del>(CFS) Correlation-based Feature Selection 
- [ ] <del>(MRMR) Minimum Redundancy Maximum Relevance 
  - [ ] <del>Minimum mutual information between features
  - [ ] <del>Maximal mutual information between the classes and the features

### 4. Learning
- [ ] Decion Trees
- [ ] Bayesian
- [ ] K-nearest
- [ ] MLP
- [ ] SVC
- [ ] Fuzzy basis function + Fuzzy Inference System
- [ ] Boosting + Bagging models

### 5. Evaluation 
- [ ] Cross Validation 
- [ ] Binary Classification where positive is the desired class and negative all the others







