# Introduction_to_AWS

This is an Introductory to Amazon Web Service. Nowadays, when you are applying for machine learning jobs, hiring managers ask you if you are familiar with AWS/Azure/Google cloud Platform? 

If you spend long time on research and you are not familiar with producing applications, you can follow up the following steps to learn AWS quickly as I did. 

To learn the machine learning pipiline in AWS

https://www.aws.training/SessionSearch?pageNumber=1&courseId=38910

Even if you do not have much knowledge of machine learning, by the end of the course, you will have successfully built, trained, evaluated, tuned, and deployed an ML model using Amazon SageMaker that solves their selected business problem. 

I also recommend to take these courses to learn AWS with computer vision and machine learning.
a)
https://www.coursera.org/projects/deploy-a-video-indexing-application-using-amazon-rekognition
b)
https://www.coursera.org/projects/object-detection-sagemaker
c)
https://www.coursera.org/projects/semantic-segmentation-sagemaker
d)
https://www.coursera.org/projects/image-classification-sagemaker
e)
https://www.coursera.org/learn/aws-computer-vision-gluoncv

f)
https://www.coursera.org/learn/aws-machine-learning   

-4 hours course

-How to build intelligent applications using Amazon AI services like Amazon Comprehend, Amazon Rekognition, Amazon Translate and others.

-How to build, train and deploy a model using Amazon SageMaker with built-in algorithms and Jupyter Notebook instance

-Amazon AI-computer Vision, Amazon AI-NLP


starting with course f: 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------

AI>ML>DL: AI mimics cognitive human actions. To do this, we need knowledge engineering and software programs  which receive data and process to make pridictions. Based on results models learn over time and make decisions. In ML, we need uncorrelated data or distictive features to feed model. In deep learning, with feeding more data, models get better analytics and better products without feature extraction.

APPLICATION Services:

AWS has some services for Vision: Amazon Rekognition, Speech: Amazon Polly, Chat: Amazon lex, Transcribe, Translate, Comprehend

e.x.: Amazon Rekontion has templates for face recognition, object detection, etc.
 
Functions for still imges : detect faces, detect labels, detec moderation labels, detect texts, index faces, , Recognize celebrities, search faces, search faces by image
      
  
  
FARMAEWORKS & INTERFACES:

Aws has Engines: Apache MXnet, TensorFlow, Caffe, Theano, Pytorch, CNTK, keras, gluon


PLATFORM Services:

AWS Platforms: Amazon sagemakers, Amazon ML, Sparke & EMR, Kinesis, Batch, ECS


--------------------------------------------------------------------------------------------------------------------------------------------------------------
To choose ML algorithms: 

*There are different ML models including supervise, unsupervised, reinforcement (Q-learning, SARSA) and deep learning models. Models can be used for classifications (Binary, multiclass) or regression. 

*There are different Deep leraning models including Resnet for image classification, RNN for text summerization, translation, etc.

*Data visalization helps to figure out if feeding data is enought clean and what to do in case of missing data? You have to feed data to the model with shuffeling and randomizing because you do not want bias model with sequential data.

*Bias is comparing pridicted value and acual value, and variance is performance of model for unseen data.

*accuracy is derivative from actual value and precision is ability of reproducing similar results. 


Amazon sage maker cover entire pipline : 

1- Data collection and Integration, 2- Data prepration 3- Data visualization ad Analytics, 4- Feature selection and engineering 5-model training 7- model evaluation
8) prediction. 

has different machine learning models including supervised (MLP, SVM) and unsupervised (Decision trees, clusterings likes k-means, PCA, etc.) models.

-------------------------------------------------------------------------------------------------------------------------------------------------------------
Deeplens Console

1) AWS sagemaker: Train and validate custom model or import a pre-train model 
2) Aws Lambda: Create a project function to make inference (prediction, inference, show results)
3) AWS DeepLens: Create a computer vision application with a model and inference function
4) AWS green grass: Deploy the application project a lambda runtime



--------------------------------------------------------------------------------------------------------------------------------------------------------


1- creat an acount in aws.amazon.com

First, you need to create a AWS acount which requires valid email address as root acount and credit card. choose basic plan among support plans( Basic, developer, business) if you do not want to pay.

Amazon SageMaker Python SDK is one of tools for traing and deploying model.

2-To store your data, build a bucket in s3 using Amazon SageMaker in Amazon Management Console . You will push your data in the bucket and will train your model on these data

bucket has secret id and key id (our credentials)

3- Create Notebook instance , you can choose standard type if you do not want to pay. other types like accelerators will charge you.
please make sure that the status of notebook is "stoped", otherwise Amazon will charge you.

4- you can use build-in frameworks for your model or use your own code in your laptop.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Amazon Sagemaker Grondtruth is for automatic labeling 

Amazon sagemaker Neo address some challenges, so that costumers do not need to optimize frameworks for diffrent platforms (convert differnt frameworks including pytorch, tensorfeow, etc to portable code which is very fast). It uses Neo compiler and shared object library. 

Amazon sagemaker hyperparameter Model tuning

e.x. trees: depth, number, boosting step and size

e.x. clustering: Nuber of clusters, initialization

e.x. NN: Hyperparameters are learning rate, layers, regularization, drop-out

Tuning can be done manually (geuss and check, experience, intuition, heuristics), Brute force (Grid, Random, Sobol)


# Amazon SageMaker

https://www.linkedin.com/learning/learning-amazon-sagemaker/machine-learning-with-amazon-sagemaker

















