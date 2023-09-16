# Natural-Language-Processing-with-Tensorflow
- My code solutions and models made by me for assignments as part of the course <b> Natural Language Processing with Tensorflow </b> offered by `Deeplearning.ai` on Coursera

### Week 1:
- Simple pre-processing of text using the `BBC Text Archive`
- Implemented standard pre-processing using Tensorflow such as tokenisation, padding, truncating and removing stopwords.

### Week 2:
- Used functions for pre-processing text on the `BBC Text Archive` using functions defined from Week 1.
- Prepared a basic architecture for performing multi-class classification on the pre-processed dataset.
- The architecture comprised of an `Embedding` layer and a `GlobalAveragePooling1D` layer.
- Used a `Sparse Categorical Cross Entropy` function as the loss function.

### Week 3:
- The task was to perform binary text classification using the `Sentiment140` dataset which consists of 1.6 million tweets.
- GLoVe embeddings were used to prepare text-embeddings for the vocabulary.
- Created an architecture with a Dropout of `0.2` followed by a layer for `1D Convolution` and one for `Max Pooling`.
- This was followed by a `LSTM` layer whose output was activated by `sigmoid` to perform classification.

### Week 4:
- The task was to create a model that will predict the next word in a text sequence apart being trained on a corpus of Shakespeare's sonnets.
- The architecture for this exercise comprised of a simple `GRU` layer followed by 2 dense layers with `ReLU` and `Softmax` activation respectively.
