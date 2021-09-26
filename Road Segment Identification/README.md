# Road Segment Identification
The objective of the challenge is to detect is there is a a road in a satellite pitcure or not.

To tackle the problem, first I used created dataset class using pytorch and defined the list of augmentations. Then I created my own model class which consists of 3 convolution layers which gave me approximately 80 ROC_AUC score on the validation data. 

After that , I used pretrained wide resnet from torchvision in my model which gave me way better results with approcimately 90 ROC_AUC score
