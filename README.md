# imageclassifier_leaves
CNN mobilenet classifier re-trained on maize leaves
The dataset used was downloaded from Plant Village by spMohanty: https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color
The code used was obtained from another repo. I made only slight modifications to the work of Pulkit Sharma from this blog https://www.analyticsvidhya.com/blog/2019/04/build-first-multi-label-image-classification-model-python/

### Key differences in this work from Pulkit Sharma's
#### 1
My sigmoid layer has 2 outputs as opposed to Pulkit's, which has 25. ie, I changed the final line of code in the CNN architecture to 2
#### 2
Since I had very clear pictures and only 2 varieties (sick and healthy images of maize), I reduced the number of epochs to 2, from 10
