# A distributed approach to meteorological predictions: addressing data imbalance in precipitation prediction models through federated learning and GANs
This repository is the source code for the paper implemented in Python. The link to access the paper:
https://link.springer.com/article/10.1007/s10287-024-00504-3 (springer.com)
https://arxiv.org/pdf/2310.13161 (arxiv.org)

## Abstract

The classification of weather data involves categorizing meteorological phenomena into classes, thereby facilitating nuanced analyses and precise predictions for various sectors such as agriculture, aviation, and disaster management. This involves utilizing machine learning models to analyze large, multidimensional weather datasets for patterns and trends. These datasets may include variables such as temperature, humidity, wind speed, and pressure, contributing to meteorological conditions. Furthermore, it’s imperative that classification algorithms proficiently navigate challenges such as data imbalances, where certain weather events (e.g., storms or extreme temperatures) might be underrepresented. This empirical study explores data augmentation methods to address imbalanced classes in tabular weather data in centralized and federated settings. Employing data augmentation techniques such as the Synthetic Minority Over-sampling Technique or Generative Adversarial Networks can improve the model’s accuracy in classifying rare but critical weather events. Moreover, with advancements in federated learning, machine learning models can be trained across decentralized databases, ensuring privacy and data integrity while mitigating the need for centralized data storage and processing. Thus, the classification of weather data stands as a critical bridge, linking raw meteorological data to actionable insights, enhancing our capacity to anticipate and prepare for diverse weather conditions.
![image](https://github.com/ElahehJafarigol/Federated-Learning/assets/64182149/ad4d83c9-dbc8-48da-bd06-d74f51f02fb0)

## Overview of the federated imbalanced learning problem. 
We address the issue of imbalanced learning in a federated setting by generating samples of the minority class using 5 data augmentation
methods. The local stations train the balanced data, and the encrypted model weights are sent to the global server for aggregation. 
The results of balanced data training are compared with those of imbalanced data in the federated learning framework
![image](https://github.com/ElahehJafarigol/Federated-Learning/assets/64182149/d885bd20-d351-4426-9b63-b101a6a0e57d)

![image](https://github.com/ElahehJafarigol/Federated-Learning-GANs/assets/64182149/8964ac44-d5b3-43b4-8b0a-119926ad351c)
