# DLAIprojectBatchNorm
The file Untitled.ipynb contains all the functions used in BatchNorm.ipynb and the two should be put in the same folder. 
BatchNorm.ipynb will train 3 networks:
- one where all the weight are trainable. We train it for 300 epochs and use Adam with lr of 0.001 as optimizer and StepRL with \gamma of 0.1 and step size 0f 160 as scheduler. 
- one where only the BatchNorm weights are trainable. We train it for 200 epochs and use Adam with lr of 0.001 as optimizer and no scheduler and then train it for other 150 with the same optimizer and StepRL with \gamma of 0.1 and step size 0f 51 as scheduler.
- one with the trainable weights randomly selected in the linear layers and th number of trainable parameters is the same number of BN weights. We train it for 200 epochs and use Adam with lr of 0.001 as optimizer and StepRL with \gamma of 0.1 and step size 0f 50 as scheduler.
