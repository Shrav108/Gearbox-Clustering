# Gearbox-Clustering
Time Series Culstering using Autoencoders of Gearbox Fault Data which are not labelled.

Data Reference: 2009 PHM Data Challenge

Data Description:
  1. The Data was collected over different loading conditions and was obtained be accelerometer.
  2. Data were collected at 30, 35, 40, 45 and 50 Hz shaft speed, under high and low loading.
  3. A total of 560 Files were present.
  4. The data is unlabelled. So unsupervised method has to be used to group the data to 5 different categories.

Method:
  1. There are 560 CSV Files with acceleration data.
  2. We use an autoencoder to bring down the dimensionality of the data.
  3. Then we feed the crushed data to a time series clustering K-means algorithm and obtained the clustered files.
