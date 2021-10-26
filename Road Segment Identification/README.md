# Road Segment Identification
The objective of the challenge is to detect is there is a a road in a satellite pitcure or not.

To tackle the problem, first I created dataset class using pytorch and defined the list of augmentations. Then I created my own model class which consists of 3 convolution blocks which gave me approximately 80 ROC_AUC score on the validation data. 

After that , I used pretrained wide resnet from torchvision in my model which gave me way better results with approximately 90 ROC_AUC score
