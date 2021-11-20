# DescNet

Descriptor Convolutional Neural Network

# Tree Structure

src:
<br>
|   config.zip `.json file with all user configurations accessed by training.ipynb file` <br>
|   inference.ipynb `Script to produce some inferences` <br>
|   training.ipynb `Main script to build and training models` <br>
|   learning_rate_range_test.ipynb `Script to test Learning Rate Range` <br>
|   lr_schedulers.zip `Learning Rate Schedulears` <br>
|   <br>
+---Datasets `Folder to stores all datasets used in this project` <br>
|   <br>
+---Models `Folder to stores all models build in this project` <br>
|   <br>
+---Outputs `Folder to stores all outputs/results from models build in this project` <br>
|   <br>
+---Pretrained `Folder to stores checkpoints from models build in this project` <br>
|   <br>
\---utilities.zip `Utility Library` <br>
    | <br>
    +---dataset  `Module to manipulate datasets` <br>
    | <br>
    +---descriptors `Module to stores all function related with descriptors manipulation` <br>
    | <br>
    +---global_variables `Module to stores all global variables used in this project` <br>
    | <br>
    +---local_feature_detection `Module to stores the Local Feature Detection (LFD) Layer` <br>
    | <br>
    +---local_feature_reduction `Module to stores the Local Descriptor Convolution (LDC) Layer` <br>
    | <br>
    +---logfile `Module to stores all function related with logfile` <br>
    | <br>
    +---reducers `Module to stores all function related with reducers manipulation` <br>
    | <br>
    +---residual_neural_network `Module to stores ResNet model` <br>
    | <br>
    +---tensorflow_functions `Module to stores all function related with TensorFlow` <br>
    | <br>
    +---timer `Python Timer Class` <br>
    | <br>
    +---visualizations `Module to stores all function related with visualizations and save figures` <br>

# How to use?

1. Configure the parameters in config.json
2. Train the model using python training.ipynb
3. Evaluate the model on test dataset or custom dataset using: inference.ipynb

# TODO:

:white_large_square: Implement Dictionary Learning  in scikit-cuda <br>
:white_large_square: Rephrase use of use_desc_block parameter <br>
:white_large_square: Solve MNIST confusion matrix plot problem <br>
:white_large_square: PEP8 and PEP257 Conventions <br>
:white_large_square: Generate requirements.txt file <br>
:white_large_square: Plot ROC-AUC <br>
:white_large_square: Plot Filters <br>
:white_large_square: Plot Feature Maps <br>
:white_large_square: Add RMSE metric to custom objetcs to allow model retraining <br>

# Referenes:

- [Return number of files in directory and subdirectory](https://stackoverflow.com/questions/16910330/return-number-of-files-in-directory-and-subdirectory "Return number of files in directory and subdirectory")
- [Google Colaboratory: misleading information about its GPU](https://stackoverflow.com/questions/48750199/google-colaboratory-misleading-information-about-its-gpu-only-5-ram-available "Google Colaboratory: misleading information about its GPU")
- [Making two seaborn countplots that share the same axis](https://stackoverflow.com/questions/56347698/making-two-seaborn-countplots-that-share-the-same-axis "Making two seaborn countplots that share the same axis")
- [How do I change the keys of this dictionary?](https://stackoverflow.com/questions/2213334/in-python-i-have-a-dictionary-how-do-i-change-the-keys-of-this-dictionary "How do I change the keys of this dictionary?")
- [Loading Custom Image Dataset for Deep Learning Models](https://towardsdatascience.com/loading-custom-image-dataset-for-deep-learning-models-part-1-d64fa7aaeca6 "Loading Custom Image Dataset for Deep Learning Models")
- [Multi-GPU and distributed training](https://keras.io/guides/distributed_training/ "Multi-GPU and distributed training")
