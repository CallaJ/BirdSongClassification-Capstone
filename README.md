# Capstone Project
In this project I will test different models to answer the question "How can we use machine learning to identify a bird by it's song?". 

This is an interesting problem to solve - bird song is not static, having the features of time and direction.

My original thought was to apply that question to the avian population in my region - but I did not know just how sparse the available data is! 

So far, I have learned how to convert audio files into spectrograms and am working on wrangling the raw data into numpy arrays without blowing up my system or running out of memory. I have some sample audio in addition to the publically available (read: kaggle, xeno-canto) sets for testing. 

Using the the kaggle numeric bird song dataset, I have protoyped some ML models. I am using the F1 score and classification reports to choose the best models. Some models 
have difficulty with some genii - so I have some more questions to answer! Why are certain genii problematic? What can I do to increase the likelihood of a TP by using augmentation on the audio file? 


