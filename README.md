# Neural_Network_Charity_Analysis
## Purpose 
### The purpose of this repository is to analyze if the money for charities funded from Alphabet Soup was used successfully. 
## Results
* The Target Varialble for our analysis is the 'IS SUCCESSFUL' column in our dataframe. This column lets us know if the money given to the charity was used successfully. 
* The features ouf our model are application type, affiliation, classification, use case, organizatiohn, income_amt, ask_amt, and special considerations. 
* The columns that are not targets or features and can be removed are Name, EIN, and Status can be removed from out dataframe. 

Compiling, Training, and Evaluating the Model
* In my attempt numbe one, I increased the number of epochs from 100 to 150 while keeping two layers and then neuron numbers at 80 for hidden layer 1 and 30 for hidden layer 2. This produced an accuracy of 0.43. 
<img width="668" alt="Attempt 1" src="https://user-images.githubusercontent.com/100246124/177197450-2a35c04a-50bd-4176-ab1c-3c55702a7de8.png">

* For attempt 2 I doubled the number of neurons t0 160 for layer 1 and 60 to layer 2. This produced an accuracy of 0.68. 
<img width="654" alt="Attempt 2" src="https://user-images.githubusercontent.com/100246124/177197481-6092e114-a906-43cb-8d95-8db80f52d3e7.png">

* For attempt 3 I added a third layer and each layer had 160, 60, and 30 neurons. This produced an accuracy of 0.53. 
<img width="673" alt="Attempt 3" src="https://user-images.githubusercontent.com/100246124/177197486-c94a9a33-548d-4536-96be-b5b3d93bab13.png">

* For attempt 4 I again added a third layer. The nuerons were 100, 30, and 10. This produced an accuray of 0.73. For layer 2, the activation was changed to 'stigmoid'. While all 4 attempts were unsuccessful in producing an accuracy of 0.75, the 4th attempt was the best one. 
<img width="641" alt="Attempt 4" src="https://user-images.githubusercontent.com/100246124/177197489-a2f37c28-d14f-4557-a592-334042131857.png">

## Summary 
* Even though there was multiple attempts, the deep learning model was unsuccessful at resulting in a 0.75 accuracy. 
* One alternative that we an try to make our model more accurate is to use the Random Forest Classifiers. The reason for this is that RFC because this type of ensemble learning model can easily handle outliers and nonlinear data. RFC can use a number of decision trees and combine their output to be able to make a final classificationdecision. 
