# Corona_virus_prediction

Covid19 detection in X-ray images using Machine Learning

After I read that Alibaba's new AI system can detect coronavirus in seconds with 96% accuracy, I was curious to do the same using ML. However, I was unable to find a proper dataset. Then everybody's favorite Adrian Rosebrock dropped a bomb of an article on the detection of Covid19 in X-ray images. The dataset he created contains 50 images(25 positive and 25 negative images), even though it is small it is good to start things off with.



For the training, I used a KNN classifier and fine-tuned to find the best fit model for the data I've obtained 100% classification accuracy. But as I mentioned earlier, the dataset is too small. We may obtain more data in the next days.



The code was built with Scikit Learn and it can be deployed on a web app using flask. I have attached the dataset with the code too.

Link to Adrian's post => https://lnkd.in/ejNCzaF
