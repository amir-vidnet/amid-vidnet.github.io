# AMIR: Active Multimodal Interaction Recognition from Video and Network Traffic in Connected Environments

[paper] [code] [datasets] [models]

## Abstract

Activity recognition using video data is widely adopted for elder care, monitoring for safety and security, and home automation. Unfortunately, using video data as the basis for activity recognition can be brittle, since models trained on video are often not robust to certain environmental changes, such as camera angle and lighting changes. 

There has been a proliferation of network-connected devices in home environments. Interactions with these smart devices are associated with network activity, making network data a potential source for recognizing these device interactions. 

This paper advocates for the synthesis of video and network data for robust interaction recognition in connected environments. We consider machine learning-based approaches for activity recognition, where each labeled activity is associated with both a video capture and an accompanying network traffic trace. 

We develop a simple but effective framework AMIR (Active Multimodal Interaction Recognition) that trains independent models for video and network activity recognition respectively, and subsequently combines the predictions from these models using a meta-learning framework. Whether in lab or at home, this approach reduces the amount of “paired” demonstrations needed to perform accurate activity recognition, where both network and video data are collected simultaneously. Specifically, the method we have developed requires up to 70.83% fewer samples to achieve 85% F1 score than random data collection, and improves accuracy by 17.76% given the same number of samples.

## Method Overview


## Datasets
![The IoT Lab.](assets/imgs/iotlab.png)

![Devices.](assets/imgs/device.png)

![Activities.](assets/imgs/activity.png)

* Feature set

## Models

![](assets/imgs/confusion.png)

![](assets/imgs/prioritization.png)


## Citation

If you use our datasets/feature sets/models/code, please cite it as:

```markdown


```

## Questions 

If you have questions about this work, please contact `shinanliu@uchicago.edu`.

