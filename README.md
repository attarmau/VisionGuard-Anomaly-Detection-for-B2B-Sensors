Anomaly detection (AD) is a crucial task in mission-critical applications such as fraud detection, network security, and medical diagnosis. Anomaly detection on visual data like images, videos, and satellite imagery, is particularly challenging task due to the high dimensionality of the data and the complexity of the underlying patterns. Yet visual anomaly detection is essential for detecting defects in manufacturing, identifying suspicious activity in surveillance footage, and detecting abnormalities in medical images.

In this walkthrough, you'll learn how to perform anomaly detection on visual data using FiftyOne and Anomalib from the OpenVINO™ toolkit. We'll use the MVTec AD dataset for demonstration, which contains images of various objects with anomalies like scratches, dents, and holes.

The notebook covers the following:

Loading the MVTec AD dataset in FiftyOne
Training an anomaly detection model with Anomalib
Evaluating anomaly detection models in FiftyOne
