# Food Recipe Recommendation Model
A model for recommending food recipes using the Cosine similarity

## Resources
Kaggle Dataset [Link](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions)

# constraints
Since the model is being trained and used locally, the available resources are pretty limited. The actions took to take the best possible outcome is as follows,

 - Limited the number of ingredients per recipe to less than 6
 - It reduces the number of lines from 163,000 to 25,000

## Output

**similarities.csv**

A file containing cosine-similarities between each recipe record. Using that it's possible to find the best cosine-similarity value for any given recipe from this output.