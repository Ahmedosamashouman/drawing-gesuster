# drawing-gesuster
Ai model that detect drawing for finger movement then translate the text or shapes or math eqn into output

 In this section you should write the following:

the idea of project is hand drawn math gesture , in this project we detect
 hand and finger movement and draw using lib like mediapipe and opencv
 and hand_tracker lib then predict the geo shapes or Eqns using Cnn models
weusetwotypes of data (minsit & hand drawn shapes)
in hand drawn shapes we use only 4 classes
 (circle,triangle,rectangle,square)
 
2) Challenges in the dataset (including pre-processing phase):--
 The dataset challenge in the variety so we apply augmentation on it
 another problem that dataset is two clear like in shapes if we put text
 behind the shape the predicting performance collapse suddenly due to
 the available dataset is only clear image of shapes
 3) Processing Phase:--
 weuseCnninbothtwomodels because it’s fit the canvas system
 AConvolutional Neural Network (CNN) is a type of deep learning
 model primarily used for analyzing visual data. It mimics the human
 brain's ability to recognize patterns and features in images, making it
 highly effective for tasks like image classification, object detection,
 and segmentation. CNNs consist of convolutional layers that extract
 features, pooling layers that reduce dimensionality, and fully
 connected layers for final decision-making. Their hierarchical
 structure enables them to learn complex patterns, starting from
 simple edges to intricate details.
 4) Comparisons:
in Eqn_recognetion model we use another dataset
 (handwrittenmathsymbols ) and another cnn model based on it but we
 face low performance than the minist model so keep it for now
 5) Results:
mainly we don’t have accurate results bec we are tracking system but
 the accuracy of shape_classifer model in his own data is 95%-98%
 6) Future Plan:--
wewill do some updates to hand tracking and finger movement
 also we need to upgrade or model and dataset to be able to
 detect and solve complex Equations :
 by using api to generative Ai model
 building or LLMs model
7) References:----
https://en.wikipedia.org/wiki/Convolutional_neural_network
 https://github.com/google-ai-edge/mediapipe
 https://www.kaggle.com/datasets/reevald/geometric-shapes-mathematic
 s
 https://www.kaggle.com/datasets/hojjatk/mnist-dataset
