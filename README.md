# textgeneration
1. Data Preprocessing:

Expand Contractions: Handle contractions for better tokenization.
Tokenization: Convert sentences and target texts into tokens.
Padding: Ensure uniform sequence lengths with padding.

2. Word Embeddings:

Train a Word2Vec model using Gensim to convert tokens into dense vectors.

3. Model Architecture:

Embedding Layer: Convert words into dense vectors.
GRU Layer: Capture sequential dependencies in the data.
Dense Layer: Produce probability distribution over the vocabulary for the next word prediction.

4. Training:

Split data into training and validation sets.
Train the GRU model on the tokenized and padded sequences.

5. Text Generation:

Use the trained model to generate text sequences based on a seed input
