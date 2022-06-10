# CNN-for-Breast-Cancer-IDC-
# CONVOLUTION NEURAL NETWORKS FOR BREAST CANCER DIAGNOSIS

Early detection of breast cancer is essential for proper treatment of the illness. Often, radiologists
find it very difficult to diagnose the illness from the histopathology images of the patients, due to
the difficulty of interpreting the screening images correctly. Consequently, this may lead to a high
death rate among women, in general. Thus, we propose, an automatic breast cancer detection
system using artificial intelligence. More precisely, we have implemented a Convolution Neural
Network model from scratch. The trained model achieved a prediction accuracy of 84.44%.
Furthermore, transfer learning models such as Resnet-50 in particular has been applied to the
dataset, and resulted in a prediction accuracy of 94%.

# Dataset

The dataset consists of 277, 524 RGB image patches of size 50 × 50 pixels that were derived from
162 breast histopathology samples stained by H&E [Janowczyk and Madabhushi, 2016]. These
images are small patches that were extracted from digital images of breast tissue samples. The
breast tissue contains many cells but only some of them are cancerous. Each patch file name is
of the format: uxXyYclassC.png. Where u is the patient ID, X is the x−coordinate of where
this patch was cropped from, Y is the y−coordinate of where this patch was cropped from, and
C indicates the class where 0 is non-IDC and 1 is IDC. 

![](image/data-images.png)


# CNN from scratch
![](image/cnn1.png)


# Resnet-50
![](image/resnet-acc.png)


# VGG16
![](image/vgg16-acc.png)

# Conclusion
A method for invasive ductal carcinoma diagnosis using histopathology images was proposed using a computer-aided tools based on deep learning algorithms. The model helps to detect whether the histopathology image of the patients is malignant or benign. Different types of models were trained on the data set; a CNN model built from scratch and models from transfer learning. These models were trained on AIMS GPU server, and the pre-trained model Resnet-50 has shown a good performance with an accuracy of $94\%$. This AI approach of detecting cancers might be implemented at the hospital or clinic to accurately diagnose patients. Thus reducing human mistakes in the process.
