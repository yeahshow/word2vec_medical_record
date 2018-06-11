# word2vec_medical_record

This project aim to utilize neural network to analyze sequence input from structured medical records, encode it with 1D conv layer, LSTM layers and generate output in the following patterns:

Categorical output

To give classification output via a softmax layer from encoded input of structured medical record text. For example, classfication output will suggest the best CT imaging exam protocol, like a recommendation system. Each input dataset already has a label of best study protocol given by a specialized medical doctor(plain text), therefore converting them into one-hot vector enables supervised training of a classification model. 

