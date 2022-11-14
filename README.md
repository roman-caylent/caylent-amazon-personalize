# caylent-amazon-personalize
Amazon Personalize samples and POCs

###
Amazon Personalize allows developers to quickly build and deploy curated recommendations and intelligent user segmentation at scale using machine learning (ML). Because Amazon Personalize can be tailored to your individual needs, you can deliver the right customer experience at the right time and in the right place.

![image](https://user-images.githubusercontent.com/96081140/201748257-ad0e79b0-b76a-4e58-8b8d-f04262ddc8f8.png)


Following this link, create a repo on Caylent’s GitHub account and deploy the project running the following commands:

Clone the Amazon Personalize Samples repo

git clone https://github.com/aws-samples/amazon-personalize-samples.git

Navigate into the next_steps/operations/ml_ops/personalize-step-functions directory

cd next_steps/operations/ml_ops/personalize-step-functions

Build your SAM project. Installation instructions 

sam build

Deploy your project. SAM offers a guided deployment option, note that you will need to provide your email address as a parameter to receive a notification.

sam deploy --guided

Navigate to your email inbox and confirm your subscription to the SNS topic






