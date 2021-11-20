# DescNet

Descriptor Convolutional Neural Network

# Tree Structure

src:
|   config.json `.json file with all user configurations accessed by training.ipynb file`
|   inference.ipynb `Script to produce some inferences`
|   training.ipynb `Main script to build and training models`
|   
+---Datasets `Folder to stores all datasets used in this project`
|                       
+---Models `Folder to stores all models build in this project`
|                       
+---Outputs `Folder to stores all outputs/results from models build in this project`
|                   
+---Pretrained `Folder to stores checkpoints from models build in this project`
|                       
\---utilities `Utility Library`
    |   
    +---dataset  `Module to manipulate datasets`
    |           
    +---descriptors `Module to stores all function related with descriptors manipulation`
    |           
    +---global_variables `Module to stores all global variables used in this project`
    |           
    +---local_feature_detection `Module to stores the Local Feature Detection (LFD) Layer`
    |           
    +---local_feature_reduction `Module to stores the Local Descriptor Convolution (LDC) Layer`
    |           
    +---logfile `Module to stores all function related with logfile`
    |           
    +---reducers `Module to stores all function related with reducers manipulation`
    |           
    +---residual_neural_network `Module to stores ResNet model`
    |           
    +---tensorflow_functions `Module to stores all function related with TensorFlow`
    |           
    +---timer `Python Timer Class`
    |           
    +---visualizations `Module to stores all function related with visualizations and save figures`

# How to use?

1. Configure the parameters in config.json
2. Train the model using python training.ipynb
3. Evaluate the model on test dataset or custom dataset using: inference.ipynb

# TODO:

<input type="checkbox" disabled /> Implement Dictionary Learning  in scikit-cuda
<input type="checkbox" disabled /> Rephrase use of use_desc_block parameter
<input type="checkbox" disabled /> Solve MNIST confusion matrix plot problem
<input type="checkbox" disabled /> PEP8 and PEP257 Conventions
<input type="checkbox" disabled /> Generate requirements.txt file
<input type="checkbox" disabled /> Plot ROC-AUC
<input type="checkbox" disabled /> Plot Filters
<input type="checkbox" disabled /> Plot Feature Maps
<input type="checkbox" disabled /> Add RMSE metric to custom objetcs to allow model retraining

# Referenes:

- [Return number of files in directory and subdirectory](https://stackoverflow.com/questions/16910330/return-number-of-files-in-directory-and-subdirectory "Return number of files in directory and subdirectory")
- [Google Colaboratory: misleading information about its GPU](https://stackoverflow.com/questions/48750199/google-colaboratory-misleading-information-about-its-gpu-only-5-ram-available "Google Colaboratory: misleading information about its GPU")
- [Making two seaborn countplots that share the same axis](https://stackoverflow.com/questions/56347698/making-two-seaborn-countplots-that-share-the-same-axis "Making two seaborn countplots that share the same axis")
- [How do I change the keys of this dictionary?](https://stackoverflow.com/questions/2213334/in-python-i-have-a-dictionary-how-do-i-change-the-keys-of-this-dictionary "How do I change the keys of this dictionary?")
- [Loading Custom Image Dataset for Deep Learning Models](https://towardsdatascience.com/loading-custom-image-dataset-for-deep-learning-models-part-1-d64fa7aaeca6 "Loading Custom Image Dataset for Deep Learning Models")
- [Multi-GPU and distributed training](https://keras.io/guides/distributed_training/ "Multi-GPU and distributed training")