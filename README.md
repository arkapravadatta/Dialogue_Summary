Project: Dialogue Summarization using LSTM and BART Models
Excited to share my latest project where I built and compared three models for dialogue summarization:

1️⃣ A custom Seq2Seq LSTM with attention
2️⃣ Facebook’s BART (bart-large-cnn)
3️⃣ A fine-tuned BART on dialogue data (bart-large-cnn-samsum)

The goal of this project is to take a conversation and condense it into a concise summary while retaining the key ideas and context. I implemented and evaluated the performance of traditional RNN-based models and modern Transformer models for the task of dialogue summarization.

Key Features:
Data Preprocessing: Tokenization and sequence padding for dialogue and summary texts, preparing the data for model training.

LSTM Model: Uses a sequence-to-sequence architecture with LSTM layers and attention to generate summaries.

BART Models: Implements both the general-purpose BART model and a fine-tuned version specialized for dialogue summarization, leveraging state-of-the-art Transformer architecture.

Evaluation: Performance evaluated using ROUGE-1 scores, with visualizations comparing the results of LSTM vs. BART models.

Summary Generation: Given an input dialogue, both the LSTM and BART models predict concise summaries word by word, with the ability to compare the outputs from both architectures.

Technologies Used:
TensorFlow/Keras: For building and training the LSTM model.

Hugging Face Transformers: For implementing and fine-tuning BART models.

Python: The primary programming language for data processing, model development, and deployment.

NumPy: For numerical operations and sequence manipulation.

Matplotlib: For visualizing training metrics and model comparison.

ROUGE-1 Scores: Used for evaluating and comparing the models' performance in summarization tasks.

Key Takeaway:
The comparison of LSTM vs. BART revealed that Transformer models (BART) significantly outperform traditional RNNs for dialogue summarization tasks, highlighting their potential in natural language processing applications.

