# machinelearning
In this exercise we are going to build a model which determines the probability of the classe variable in the pml-testing set. 
I initially was going to use a multilogistical regression equation but given the lack of ability to create a clearly defined model I used the tree function. 
The regression tree is given by 
modfit=train(classe~.,method="rpart", data=nike)

After testing the significance of the columns I only used 3 columns 
"magnet_dumbbell_z","yaw_forearm","magnet_forearm_z"

Please see the HTML doc which is created by the kitr of the R markdown script for the complete code. 

