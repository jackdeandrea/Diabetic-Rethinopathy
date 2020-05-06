
## Diabetic retinopathy screening w/ Tensorflow
Me, Giacomo Deandrea, and my fellow student Giulio Quaglia realized this notebooks as a part of the Data Mining, statistical modeling and machine learning course (https://fisica-sc.campusnet.unito.it/do/corsi.pl/Show?_id=52ce)_ of the Physics of Complex Systems master degree held at University of Turin.

In particular the two notebooks refer to two different approaches used for didactic purposes:
ProvaCNN is a 'test notebook' we used to gain confidence in the tools we were about to learn, in particular keras' directory iterators and generators, how to correctly preprocess image data and so on. The CNN used was only something to try our data on.
ProvaTL, the main project, shows an example of transfer learning using Google's InceptionV3 and a small classification layer trained on top. Since the model was overfitting we augmented the images in our dataset performing some transformations, results were encouraging. We then tried a little bit of fine tuning on the last layers of Inception, which show a further improvement in performance. 

Diabetic retinopathy is one of the leading causes of blindness in the the world and affects up to 40% of diabetic patients, with nearly 100 million cases worldwide as of 2010. However, with proper detection and treatment, the effects of diabetic retinopathy can be properly addressed. For people who are diabetic but are unable to visit an optometrist, due to lack of proper healthcare infrastructure, diagnosing this dangerous condition is often difficult, costly, and time consuming. Additionally, offering a way to more quickly detect diabetic retinopathy in a primary care setting would save time and money as well. Using the freely available machine learning software library Tensorflow, this experiment aims to allow a computerized, preliminary detection based on the retinal image of a patient's eye. This Tensorflow-based implementation uses convolutional neural networks to take a retinal image, analyze it, and learn the characteristics of an eye that shows signs of diabetic retinopathy in order to detect this condition in a primary care setting.

Images from Kaggle's Diabetic Retinopathy detection challenge: https://www.kaggle.com/c/diabetic-retinopathy-detection. 
A smaller, curated version is available at https://github.com/Nomikxyz/retinopathy-dataset
