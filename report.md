The purpose of this analysis was to create a neural network that would help select applicants for funding with the best chance of success in their ventures.

* The target variable for this project was the column "IS_SUCCESSFUL"
* The features for this model were all other columns
* COlumns that should be removed for basic analysis should be 'EIN' and 'NAME'. However, more columns may be dropped which could be causing a lot of noise. Some example of columns which could compromise accuracy are: "SPECIAL_CONSIDERATIONS" and "STATUS"

* No major difference was seen by increasing the number of neurons and layers. Therefore, I chose to keep it to two hidden layers and 5 neuros each. There was also no difference in activation functions, so any of the four would suffice.
* I was not able to achieve higher than a 73% accuracy for this model.
* In order to attempt to increase model performance, I removed some columns and tried different combinations of neuros, activation functions, and hidden layers.

Overall, the results were underwhelming as I was unable to create any meaningful change in the accuracy of the model. I personally believe that the best and only way to increase accuracy in this model would be to have more relevant data.