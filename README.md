Skin cancer classifier (benign or malignant) trained with pytorch using the pretrained resnet18 model. 

The data used is from: https://www.kaggle.com/fanconic/skin-cancer-malignant-vs-benign
The data was split into training, validation and testing. 
The folder data showcases how the data was organized.

train had 1080  benign images, and 897 malignant images.
val had 360 benign images, and 300 malignant images.
test had 360 benign images, and 300 malignant images.

The code has been implemented following this pytorch documentation: https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html

Ended up with an 84% test accuracy (557/660). 
The model did a really good job at classification, showing that deep learning is changing the medical industry. Making it easier, faster, cheaper and more accurate than humans. 

Further steps is to try using different models for image classification and trying different approaches.

Overall, I am very satisified with the results. I had so much fun creating this model and I am looking forward to learning more about AI to help humans with various objectives.  