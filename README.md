![istockphoto-2139707587-1024x1024](https://github.com/user-attachments/assets/37662bb1-efdc-4158-806b-a16340f238ee)

Anomaly detection (AD) is a crucial task in mission-critical applications such as fraud detection, network security, and medical diagnosis. Anomaly detection on visual data like images, videos, and satellite imagery, is particularly challenging task due to the high dimensionality of the data and the complexity of the underlying patterns. Yet visual anomaly detection is essential for detecting defects in manufacturing, identifying suspicious activity in surveillance footage, and detecting abnormalities in medical images.

In this walkthrough, the process of performing anomaly detection on visual data using FiftyOne and Anomalib from the OpenVINO™ toolkit will be explored. The MVTec AD dataset will be used for demonstration, containing images of various objects with anomalies such as scratches, dents, and holes. In many deployment scenarios, this technique can be applied to the manufacturing industry to detect anomalies on production lines.

The files covers the following:

- Loading the MVTec AD dataset in FiftyOne
- Training an anomaly detection model with Anomalib
- Evaluating anomaly detection models in FiftyOne
