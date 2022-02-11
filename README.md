# NMA_CN
This is the group project we did in Neuromatch Academy 2021.

# About the Project
In this project, we use the dataset from Kay which includes over 2k pictures and corresponding bold responses from multiple visual cortices of the human brain. 
We aim to find the representation similarity of between visual cortices and a classical CNN, the AlexNet.

In order to do that, we finetuned a pretrained AlexNet using the pictures as input and the corresponding labels as targets at first. Then we extract the weights from the last layer to calculate representaion dissimilarity matrix (RDM). On the other hand, we performed principal component analysis on the BOLD responses matrixes. For each region of interest, we get a different matrix. Then we used the dimensionality reduced matrix to calculate the RDMs. And finally, we perform the representational similarity analysis between RDMs
