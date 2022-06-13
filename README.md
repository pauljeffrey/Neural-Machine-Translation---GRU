# Neural-Machine-Translation---GRU
Neural Machine Translation uses an encoder-decoder architecture with attention mechanism to peform translation tasks from spanish to english.

## INTRODUCTION
It uses an encoder-decoder system with attention to translate spanish text to english text.

Train_loss - 0.12
## INPUT
Spanish text

## OUTPUT
English text


# METHOD
The input text is encoded using a GRU layer and then passed to a decoder GRU that uses attention to attend to the encoded input. The final context is then passed
to the decoder GRU which outputs the translated text.

A class is created as an API to access the model directly to produce translation.

For more info on the code, model architecture and explanations, read the .ipynb file attached to this repository.
