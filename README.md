# Plant-Seedlings-Classification

Weed Control is a challenging problem these days, which is reducing the crop quality and productivity. Weeds are constantly competing for nutrients, water and sunlight. Thus, weed control must be achieved as early as possible, before the weeds begin to compete with the main crops and cause adverse eﬀects.

With the motivation to develop a system to classify plant seedlings at their early growth stages, we propose a model for the classiﬁcation of same. This approach extracts features from a given input image and classiﬁes the image as class of a weed.

I have considered 12 classes of weeds namely, 
- Common Chickweed, 
- Maize,
- BlackGrass,
- SugarBeet,
- ScentlessMayweed,
- Small-ﬂoweredCranesbill, 
- Common Wheat, 
- Cleavers, 
- Charlock, 
- Loose-Silky Bent, 
- Fat Hen and 
- Shepherd’s Purse. 

The input image is classiﬁed as one of the mentioned classes.


### Architecture 


### Results

The model is trained for 150 epochs using CrossEntropy loss and Adam optimizer along with a learning rate of 0.0001. 

The model has achieved:

• Train Accuracy : 0.9703

• Train Loss : 0.0867

• Validation Accuracy : 0.9515

• Validation Loss : 0.2188


### Kaggle link to the competition -  https://www.kaggle.com/c/plant-seedlings-classification
