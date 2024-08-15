# DFP-Dataset
This dataset is used in the paper Multi-Target Device-Free Positioning Based on Spatial-Temporal mmWave Point Cloud.
Following, we introduce the composition and implementation details of this dataset.

# Data:
1. Multi-target positioning raw data in indoor and outdoor scenarios.
   Frequency Slope(MHz/us)=62, Sample Rate(ksps)=5000, No of Frame=180.

2. Multi-target positioning raw data in NLOS scenarios.
   Frequency Slope(MHz/us)=58, Sample Rate(ksps)=6200, No of Frame=40.
   
   ![1](Fig1.png)
4. Small fan experiments raw data for evaluating measurement precision and resolution.
   Frequency Slope(MHz/us)=58, Sample Rate(ksps)=6200, No of Frame=90.

   ![1](Fig2.png)

   DFP-Dataset download link: [DFP-Dataset](https://mega.nz/folder/UTMFFDgR#zqNTpQEPRUunK6Qq3zudSg)
# Code: 
1. Fine-grained point cloud construction.
2. Multi-target tracking based on particle filter.
3. Trajectory association after multi-target close interaction.

