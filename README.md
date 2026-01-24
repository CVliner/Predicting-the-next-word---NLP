### Predicting the next word - NLP

The project about how to create a model that will predict the next word in a text sequence.

### By creation the model

Define a model architecture capable of achieving an accuracy of at least 80%.

Some hints to help do this task:

- An appropriate `output_dim` for the first layer (Embedding) is 100, this is already provided
- A Bidirectional LSTM is helpful for this particular problem.
- The last layer should have the same number of units as the total number of words in the corpus and a softmax activation function.
- This problem can be solved with only two layers (excluding the Embedding) so try out small architectures first.


After all work it is finally time to see model generating text.

Run the cell below to generate the next 100 words of a seed text.
