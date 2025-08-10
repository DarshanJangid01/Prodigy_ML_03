#SVM Image Classification – Cats vs Dogs (with VGG16 Features)
    This project uses a Support Vector Machine (SVM) to classify images of cats and dogs using deep features extracted from the VGG16 model.

#Model Overview:
    - **Feature Extractor**: Pre-trained VGG16 (without top layer)
    - **Preprocessing**: Images loaded and resized using `tensorflow.keras.preprocessing.image`
    - **Dimensionality Reduction**: PCA to reduce feature dimensionality
    - **Classifier**: Support Vector Machine (SVM) using `scikit-learn`

#Dataset:
    The dataset is sourced from Kaggle and includes thousands of labeled images.
    The link to the dataset used for training and testing the SVM is uploaded in the datasets.md fie.
    To access the data visit the link and download the dataset file train and test.
    The model asks for the path to the folder where the dataset is stored for feature extraction  and image preprocessing.

#Manual Testing:
    The model also contains a function to manually pass an image as input to the SVM and classify whether it is a dog or cat.
    
    
    
    
    



