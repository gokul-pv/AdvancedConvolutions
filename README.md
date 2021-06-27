# EVA6_Assignments_Session7
EVA6 Assignment for Session 7

This assignment uses the dataset CIFAR-10. It has the classes: ‘airplane’, ‘automobile’, ‘bird’, ‘cat’, ‘deer’, ‘dog’, ‘frog’, ‘horse’, ‘ship’, ‘truck’. The images in CIFAR-10 are of size 3x32x32, i.e. 3-channel color images of 32x32 pixels in size. 

The problem statement for this tutorial is given below

   <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/problem_statement.png?raw=true" width =700>
    <br>
    <em style="color: grey">Figure 1 : Problem Statement</em>
  </p> 

  
The **summary** of the model is shown below

  <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/model_summary.png?raw=true" width =1000>
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
    <em style="color: grey">Figure 3 : Image showing applied transformations </em>
  </p> 
  

**Result**

The training log for epoch 17 to 40 is shown below

 <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/training_log_1724.png?raw=true" width =700>
    <br>
    <em style="color: grey">Figure 4.1 : Log1</em>
  </p>
   <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/training_log_2533.png?raw=true" width =700>
    <br>
    <em style="color: grey">Figure 4.2 : Log2</em>
  </p>
   <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/training_log_3340.png?raw=true" width =700>
    <br>
    <em style="color: grey">Figure 4.3 : Log3</em>
  </p>

The test and validation loss and accuracy are shown below

 <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/loss_acc_plot.png?raw=true" width =700>
    <br>
    <em style="color: grey">Figure 5 : Loss and accuracy plots</em>
  </p>

   <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/Class_accurarcy.png?raw=true" width =1000>
    <br>
    <em style="color: grey">Figure 6 : Validation accuracy per class</em>
  </p> 


**Misclassified Images during validation**

Misclassified images during validation for all the three models are shown below


  <p align="center" style="padding: 10px">
    <img alt="Forwarding" src="https://github.com/gokul-pv/EVA6_Assignmets_Session7/blob/main/images/misclassified.png?raw=true" width =700>
    <br>
    <em style="color: grey">Figure 7 : Misclassified images</em>
  </p> 



