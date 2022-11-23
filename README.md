# Kinship-Recognition
Solving the kinship recognition problem using Siamese Network and pretrained DenseNet and ResNet models in PyTorch.

Kinship Recognition is an emerging task in Computer Vision that aims to find out if there is a kinship relationship between certain subjects through the images of their faces. The areas of application of kinship verification include **annotating images**, **organizing family albums**, **forensic investigation**, **surveillance**, and more. However, verifying kinship through facial images is challenging as such images contain high intra-variances, which vary by age, gender and other biological characteristics that are often not discriminable by the human eye. Over the years, many more and more effective methods have been developed to solve the problem.

This notebook deals with the recognition of kinship through **neural networks**, in particular using **Siamese Networks**. You can choose to use two main approaches to solve the problem: the first approach uses a **naive** Siamese network, while the second approach uses the **transfer-learning** technique to import **pre-trained networks** such as **DenseNet** and **ResNet**.

You can read the full article here: https://medium.com/@ale-mauro/kinship-recognition-using-siamese-network-c9724f5a614

# Execute the notebook
In order to execute the notebook, you have to download the data from the Kaggle Competiton (https://www.kaggle.com/competitions/recognizing-faces-in-the-wild/data) and upload the data in Google Drive.
* Upload the dataset from Kaggle in a folder "ComputerVisionProject/kinship-data/".
* Upload the notebook in the "ComputerVisionProject/" folder.

You have to choose the GPU runtime from Colab, then you can easly run all the cells of the notebook.
