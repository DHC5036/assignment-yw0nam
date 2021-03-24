Q1. Can you design a learnable positional encoding method?

Yeah, positional encoder can be designed as learnable.

Q2. What can be challenges to Transformers if input sequences are very long? Why?

According to the author, there is a upper boundary for inputs of transformer. Because it can't handle very very long sequnece. So, if length of the inputs are very long so that model can't handle that, i can preprocess to reduce the input sequence length. it can be a good choice using bert to reduce sequence length.
