Project goal: Make a pipeline which converts EEG to spectrogram and applies discriminative models 
on the spectrogram image to predict a movie character's emotions. 

Project members: 
1. Alex
2. Caleb
3. Josh
4. Tony
5. Torsten
6. Vipul 

Files: 
1. VGG19_Pipeline.ipynb: Contains EDA, spectrogram and VGG19 pipeline. 
2. EDA_and_Data_Extraction.ipynb: Contains EDA for json files and conversion of all json files into a single dataframe for the first subject's data that we were given. For the second subject it contains extracting the labels for happy/not happy for the movie greenbook and this subject. 
3. Face_NoFace_Attempt.ipynb: Contains modeling to predict whether a face is in the frame or not. Attempt was to generate face/no-face labesl for each frame of the movie given that the emotion labels for the first subject was lacking. 
4. neural_data_preprocessing.ipynb: contains cleaning, windowing and spectrogram conversion of eeg data. 
5. happy_not_happy_model.ipynb: contains a binary vgg19 fine tuned model to predict happy(0) or not happy(1). 

