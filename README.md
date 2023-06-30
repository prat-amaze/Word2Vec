# Word2Vec

# Project Overview
The word embedding project involves the following key steps:

**Word Processing**: The project takes input paragraphs and processes them by tokenizing the words and creating a vocabulary. The vocabulary represents the unique words present in the paragraphs.

**Window-Based Approach**: A window-based approach is employed to create word embeddings. This approach involves sliding a window of size 2 over the words in each paragraph. For each word in the window, the surrounding words within the window are considered as context words.

**One-Hot Encoding**: The project efficiently converts the context words into one-hot encoded vectors of length 5. Each unique word in the vocabulary is assigned a unique index, and the corresponding one-hot encoded vector is created by setting the index position to 1 and all other positions to 0.

**Word Embedding Generation**: By combining the one-hot encoded vectors for the context words, the project generates highly informative word embeddings. These word embeddings capture the contextual information within the paragraph and can be used for various analysis tasks.
