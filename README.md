# Breast-Cancer
1. Breast cancer  is the most common cancer among women worldwide accounting for 25 percent of all cancer cases
and affected 2.1 million people in 2015.:worried:
1. Early diagnosis significantly increases the chances of survival:confused:

#### Data Set Characteristics:
 - Number of Instances: 569
 - Number of Attributes: 30 numeric, predictive attributes and the class
 - Attribute Information:
      - radius (mean of distances from center to points on the perimeter)
      - texture (standard deviation of gray-scale values)
      - perimeter
      - area
      - smoothness (local variation in radius lengths)
      - compactness (perimeter^2 / area - 1.0)
      - concavity (severity of concave portions of the contour)
      - concave points (number of concave portions of the contour)
      - symmetry 
      - fractal dimension ("coastline approximation" - 1)    
   
        The mean, standard error, and "worst" or largest (mean of the three
        largest values) of these features were computed for each image,
        resulting in 30 features.  For instance, field 3 is Mean Radius, field
        13 is Radius SE, field 23 is Worst Radius.

      - class:
           - WDBC-Malignant
           - WDBC-Benign

**The key challenge in cancer detection is how to classify tumors into malignant or benign using machine learning**<br/>
  Here is Solution:triumph:
 ![image.png](https://github.com/garg525modi/Breast-Cancer/blob/master/capture.JPG)
 
 #### Why Support Vetor Machine?:frowning:

PRO | CONS
------------ | -------------
SVMs are based on the idea of finding a hyperplane that best divides a dataset into two classes | Isn’t suited to larger datasets as the training time with SVMs can be high
It only focuses on support vectors instead of all samples & Accuracy | Less effective on noisier datasets with overlapping classe 
