# Mohammed Maheer



[Profile Summary](https://profile-summary-for-github.com/user/android-kunjapppan)

 
# [Project 1: Driver Distraction Detection using Convolutional Neural Nets.](https://github.com/android-kunjapppan/Distracted-Driver-Detection-using-CNN/blob/master/Maheer_report.pdf)
<p>Distracted Driving is the major cause for several road accidents. According to the survey of the NHTSA, one among five motor vehicle crashes is due to driver distraction. To overcome this, our aim is to develop an accurate and robust system for detecting a distracted driver. In previous works, Transfer learning models like AlexNet, GoogleNet and ResNet have been used. To train the model, State Farm Driver Distraction Dataset has been used in which the actions of drivers are classified into ten categories. In the proposed work, a model from scratch is developed and trained on our dataset. Then the same AlexNet, GoogleNet, ResNet models have been used by doing Fine-Tuning and adding some extra layers to these models. Next other state-of-the-art models like Xception, VGG16, MOBILENET and ResNet50 are trained with our dataset by adding extra layers to these models and then Fine-Tuned the model. Finally, ensembled all the models to attain better accuracy and tested it on our test data. Our experimental results indicate the attainment of better accuracy.</p>

  
# [Project 2: Sentiment Analysis on Financial Data](https://github.com/android-kunjapppan/Sentiment-Analysis-on-Financial-Reports)

<p>Financial Statements are records that provide an indication of the organization’s financial status. Our main objective is to understand, analyze and interpret the basic concepts of financial statements of a company.</p> 

* Interpretation of financial ratios and their significance. 
* To Calculate Positive, Negative, Certain, Uncertain Scores
* To Calcualte the fog index
* To Calculate the precetantage of Complex words
* To calculate the Word Proportions
* To Know about Long- Term Solvency 
* To Know about Operating Efficiency
* To know about Over-All Profitability


# [Project 3: Behavioral Cloning for self driving cars](https://github.com/android-kunjapppan/Behavioral-Cloning-for-self-driving-cars)
**Implemtation of the paper "End to End Learning for Self-Driving Cars"**

<p>The overall strategy for deriving a model architecture was to drive a car through any terrain and any conditions. My first step was to use a convolution neural network model similar to the NVIDIA I thought this model might be appropriate because it was designed for autonomous vehicles to drive through all kinds of terrains. But as compared to realtime scenarios the conditions in the simulation are simpler. So I decided to reduce the model complexity further by reducing convolutional layers and dense layers. This I have done by keeping in mind that the features required by car to drive through road are extracted at initaial levels of convolutional layer and by following this approach I am able to achieve satisfactory results by using 1 convolution layer followed by 1 Dense layer. In order to gauge how well the model was working, I split my image and steering angle data into a training and validation set. I found that model had a low mean squared error on the training set but a high mean squared error on the validation set. This implied that the model was overfitting. To combat the overfitting, I have added dropout layer and maxpooling layer followed by convolution layer and I reduced number of epoches. The final step was to run the simulator to see how well the car was driving around track one. There were a few spots where the vehicle fell off the track to improve the driving behavior in these cases, I have added left and right side images with offeseted driving angle, I have cropped the image to include only required details so that noise can be reduced, I flipped images so that additional details are available while training the vehicle. At the end of the process, the vehicle is able to drive autonomously around both the tracks without leaving the road.</p>
