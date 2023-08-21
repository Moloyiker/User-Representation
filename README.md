# User-Representation
source_code








Our model is an improved version of the basic model consisting of Transformer and CNN. The number of layers in the Transformer and the size of the convolutional kernel are hyperparameters known to have an impact on the final performance of the model. Here, we perform a grid search on the number of layers in the Transformer encoder and decoder, ranging from 1 to 5, as shown in Figure~\ref{fig:10} (a) and (b). The width of the convolutional kernel is selected as 2, 4, 8, 16, 32 for testing, as shown in Figure~\ref{fig:10} (c). After experimentation, we recommend using two layers of Transformer and setting the width of the convolutional kernel to 8 for optimal performance.
