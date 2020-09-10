# Safety Helmet Detection with fastai


Tasks:
1. To implement a solution to make sure that Standard Operating Procedures are followed in manufacturing factories.
		a. Detect whether workers are wearing helmets and send real-time information about defaulters.
		b. Detect if anyone is near a restricted working space and trigger an alarm.
		c. Detect if specified doors are closed and trigger an alarm in case of malfunction.
2. Create a document that contains all the necessary content to help someone read and implement the
same solution.
		a. What type of object detectors are there?
		b. What are some SOTA methods available?
		c. What are the datasets that are publicly available?
		d. Can we create our own dataset?
		e. What are some software or techniques that we can use to label the dataset?
		f. Has someone done similar work in this area?
		g. What are some open-source codebases that people reading the document can refer to?
		h. Provide more links to blogs, articles, videos, etc. to learn more about the topic.


• Solution:
- Task 1: Object detection is a computer vision technique which we can use to identify objects in an image or video or in real-time. Now a days it is 		vigorously used in various field like surveillance, human activity detection, self-driving car etc.
		- Detect whether workers are wearing helmets and send real-time information about defaulters:
		Safety helmet are designed to protect the head against falling objects and the side of the
		head, eyes, and neck from any untoward impacts, bumps, scrapes, and electrical exposure,
		etc. So, it is necessary to wear a helmet for workers and those who are riding a
		bicycle/motorbike. So, it is better to apply object detection models to check whether a
		worker is wearing a helmet or not. The model is below:
			Library Dependencies:
			1. Pytorch >= 1.6.0
			2. Fastai <= 1.0.61
			3. Object-Detection-Fastai <= 0.0.9
			4. OpenCV >= 3.x
			5. Xml
			6. Numpy
			7. Pandas
			8. Sklearn
			Hardware Dependencies:
			1. Camera Infrared Enabled (For Night)
			2. Internet
			3. Embedded Systems (Arduino, Raspberry Pi)
			4. Server (if possible)

			Public Dataset: https://www.kaggle.com/andrewmvd/hard-hat-detection
			GitHub: https://github.com/sb-robo/Safety-Helmet-Detection

Task 2:
		1. Infrared Sensor, Ultrasonic sensor
		2. Two Dimensional SOTA method
		3. https://www.kaggle.com/andrewmvd/hard-hat-detection
		4. Yes, we can make our own Dataset
		5.
		6. Inhouse labelling, Crowd housing, Out sourcing to Individuals.
		7. https://github.com/tensorflow/models/tree/master/research/object_detection
			https://github.com/arunponnusamy/object-detection-opencv	
		8. https://nanonets.com/blog/object-tracking-deepsort/
			https://nanonets.com/blog/real-time-object-detection-for-drones/
			https://tryolabs.com/blog/tags/object-detection/
