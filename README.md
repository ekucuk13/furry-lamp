# furry-lamp
My Comp 541 term project is about replicating  Image-based Recommendation System with CNN

Summary of the project: 
The current system of recommendation engine in e-commerce involves key words, in this project the researcher presents image based product recommendation system that involves CNN. There are two main process for image-based recommendation system and these are classification and recommendation. In the classification step the images are classified into 20 predefined categories. This is done using AlexNet and VGG models where the base line is SVM.  In the recommendation step last fully connected layer of classification model is used as feature vector. Feature extraction and similarity calculation is applied on this vector. Similarity metric is taken as Jaccard Similarity and cosine similarity score. Similarity is evaluated only for the products that are in the same category. Product information data is provided by Amazon. In conclusion with the proposed study classification accuracy 0.5 and recommendation accuracy is higher than 0.5. 

