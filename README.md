# RNN_ANER
Applying Recurrent Neural Network on Arabic Named Entity Recognition

Abstract
Named Entity Recognition (NER) (also known as entity identification) is a subtask of information extraction that seeks to locate and classify elements in text into predefined categories such as the names of persons, organizations, locations, etc. NER plays an important role in many NLP problems, such as Machine Translation as it helps improve the performance of algorithms that solve these problems.

In this work, we plan to tackle Arabic NE recognition and classification with an approach using Long Short Term Memory (LSTM) neural networks. We use LSTMs’ ability to memorize long term dependencies to train a model for Arabic NE recognition, on a training dataset. The model is then used to predict the NEs for a sample of Arabic sentences in our test set. We tested our system on a pilot dataset. In its current version, it achieves a word level accuracy of 85%. More recently we trained our model on the more standard ACE 2007 dataset and achieved an F1 score of 57.54 for detecting boundaries and 53.31 for categorizing the named entity. However, adding part-of-speech as a feature reduced our performance. Overall, LSTM seems to be a promising model for Arabic NER. We plan to compare it with different existing baselines trained on other dataset. We also plan to identify an optimal feature set in order to study its impact on the accuracy of our predictor.

Thesis archived at: http://reports-archive.adm.cs.cmu.edu/anon/qatar/abstracts/16-130.html
