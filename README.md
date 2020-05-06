
## Diabetic retinopathy screening w/ Tensorflow
Me, Giacomo Deandrea, and my fellow student Giulio Quaglia realized this notebooks as a part of the Data Mining, statistical modeling and machine learning course (https://fisica-sc.campusnet.unito.it/do/corsi.pl/Show?_id=52ce) of the Physics of Complex Systems master degree held at University of Turin.

In particular the two notebooks refer to two different approaches used for didactic purposes:
ProvaCNN is a 'test notebook' we used to gain confidence in the tools we were about to learn, in particular keras' directory iterators and generators, how to correctly preprocess image data and so on. The CNN used was only something to try our data on.
ProvaTL, the main project, shows an example of transfer learning using Google's InceptionV3 and a small classification layer trained on top. Since the model was overfitting we augmented the images in our dataset performing some transformations, results were encouraging. We then tried a little bit of fine tuning on the last layers of Inception, which show a further improvement in performance.

Data was taken from https://github.com/Nomikxyz/retinopathy-dataset , a small, curated version of the original dataset you can find at https://www.kaggle.com/c/diabetic-retinopathy-detection.

Here below you can find some info about diabetic retinopathy and why studying machine learning possible solutions to this problem can be useful.

Diabetic retinopathy is one of the leading causes of blindness in the the world and affects up to 40% of diabetic patients, with nearly 100 million cases worldwide as of 2010. However, with proper detection and treatment, the effects of diabetic retinopathy can be properly addressed. For people who are diabetic but are unable to visit an optometrist, due to lack of proper healthcare infrastructure, diagnosing this dangerous condition is often difficult, costly, and time consuming. Additionally, offering a way to more quickly detect diabetic retinopathy in a primary care setting would save time and money as well.
