# Indoor Dataset: Transfer Learning vs Scratch (VGG)

Indoor scene recognition is a challenging open problem in high level vision. In this project, two VGG16 models sre used to classify 
the indoor dataset. One of these models is pretrained and the other is not pretrained. It can be obviously seen that the pretrained 
model performs much better than the untrained one. The reason behind is that, when a model is pretrained, learning new tasks is easier 
for it. The pretrained model had an acurracy of 86% on test data with 10 epochs, whereas, the model that is not pretrained had 40% 
acurracy on test data even though it had 80 epochs.   
