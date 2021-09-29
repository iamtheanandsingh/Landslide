# Landslide-Trigger-Classification
### Classification of Landslide Triggers with Random  Forest Classifier and Support Vector Machines 
 
**Abstract.** There has been a significant amount of research previously done for forecasting potential landslide occurrences based on the soil and slope of terrain, and even recent research with the use of machine learning to predict landslide susceptibility. However, there has yet to be research regarding the prediction of landslide triggers. Our research focuses on extending the existing research by determining the primary triggers for landslides in various locations around the globe. We believe that by considering the initial cause of a landslide we can extend research to better predict the likelihood of a landslide occurrence. Using a dataset of landslide incidences and their associated triggers this work summarizes two methods of implementation, Random Forest Classifier (RFC) and Support Vector Machines (SVM). We found through these methods that the proposed dataset in imbalanced and lacks features causing poor model performance. With most rainfall-triggered landslides and a shortage of data for non-rainfall triggers we implemented ADASYN on our RFC model and SMOTE with our SVM model to handle data imbalance. Our results for this multi-class classification problem show that with oversampling we were able to improve our model performance, but due to lack of data for minority classes our overall performance for both models was subpar.  