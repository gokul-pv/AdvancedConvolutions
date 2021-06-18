# EVA6_Assignments_Session7
EVA6 Assignment for Session 7

This assignment uses the dataset CIFAR-10. The problem statement is as follows

   <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/problem_statement.png?raw=true" width =700>
    <br>
    <em style="color: grey">Figure 1 : Problem Statement</em>
  </p> 
  
The **summary** of the model is shown below

  <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/model_summary.png?raw=true" width =500>
    <br>
    <em style="color: grey">Figure 2 : Model Summary </em>
  </p> 
  



**Code Explanation**

The model.py file contains the class Net which defines the CNN.

**Albumentation**

The transformation is applied using library albumentations.

  <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/Albumentations.png?raw=true" width =1000>
    <br>
    <em style="color: grey">Figure 3 : Misclassified images</em>
  </p> 
  

**Misclassified Images during validation**

Misclassified images during validation for all the three models are shown below


  <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/misclassified.png?raw=true" width =1000>
    <br>
    <em style="color: grey">Figure 4 : Misclassified images</em>
  </p> 
  
  
   <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/Class_accurarcy.png?raw=true" width =1000>
    <br>
    <em style="color: grey">Figure 5 : Validation accuracy per class</em>
  </p> 




**Result**

The training log for epoch 17 to 40 is shown below

 <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/training_log_1724.png?raw=true" width =700>
    <br>
    <em style="color: grey">Figure 6.1 : Log1</em>
  </p>
   <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/training_log_2533.png?raw=true" width =700>
    <br>
    <em style="color: grey">Figure 6.2 : Log2</em>
  </p>
   <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/training_log_3340.png?raw=true" width =700>
    <br>
    <em style="color: grey">Figure 6.3 : Log3</em>
  </p>

The test and validation loss and accuracy are shown below

 <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/loss_acc_plot.png?raw=true" width =700>
    <br>
    <em style="color: grey">Figure 7 : Loss and accuracy plots</em>
  </p>



