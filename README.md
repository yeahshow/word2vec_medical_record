# word2vec_medical_record

This project aim to utilize neural network to analyze sequence input from structured free-text medical records. At this stage, models are trained to give categorical output and optimized with categorical loss. In addition, a word embedding can be generated during training. 

Preprocessing original data for training

Preprocessing performed to remove any training data with missing item, remove non-english characters, remove all next-line character '\r\n' and assign an UUID to each set of training data.

