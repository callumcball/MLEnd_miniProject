# MLEnd Mini Project
Using the MLEnd dataset, this model that makes various predictions.


*Brief summary*: A basic solution currently using only pitch features.

*Dataset preparation*: dataset has been organised with the recordings and the corresponding emotion they are connected to.

*Dataset visualisation*: visualising accuracy and loss over epochs with NN, and use of confusion matrix as the basic visual of classification success.

*Preprocessing*:  extraction of 4 pitch features and z-score normalization.

*Model(s) description:*  basic SVM and Naive Bayes classifiers (optimise further.

*Training and validation tasks*: included in models from sklearn. 

*Performance evaluation (accuracy, confusion matrix, ROC curve, etc)*: accuracy and confusion matrix presented. (consider including an ROC curve to see if the false positive vs false negative rate can be optimised)

*Conclusions.*

-------------------------------------------------------------------

## Classifying Which Number each student said in a .wav Recording

*Brief summary*: A variation on the basic solution using the pitch features provided in the starter kit as well as using spectrograms.

*Dataset preparation*: Load wav files into drive with accompanying dataset describing details of each file; its ID, digit label, participant ID, and intonation class.

*Dataset visualisation*: wave visuals and spectrogram. Use of confusion matrix as the basic visual of classification success. As well as ROC curves and visualising accuracy and loss over epochs with NN.

*Preprocessing*: extraction of 4 features initially: power, pitch_mean,pitch_std, voiced_fr with normalisation. Then extraction of spectrograms using STFT.

*Model(s) description*: basic SVM and NB classifiers (to be optimised), then a Multi-Layered Perceptron, and finally a CNN with dropout.

*Training and validation tasks*: include splitting traing and validation dataset, which would then be used to optomised the SVC for example.

*Performance evaluation (accuracy, confusion matrix, ROC curve, etc)*: accuracy and confusion matrix presented. ROC curve and any other relevant evaluation metrics.

*Conclusions*. CNN's are very powerful and, once a basic solution like an SVM is working okay, are a great model to try with audio and/or visual data. Optimisation and fine-tuning would likely help further here. So would more expereimentation along with more data most probably.

reference: https://towardsdatascience.com/speech-classification-using-neural-networks-the-basics-e5b08d6928b7
