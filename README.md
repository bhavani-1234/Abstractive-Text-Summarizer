# Abstractive-Text-Summarizer
we fine tuned t5 transformer model for Summarization Task, where a summary of a given article/document is generated when passed through a network

It generates summary, that is close to or better than the actual summary while ensuring the important information from the article is not lost.

We used the News Summary dataset available at Kaggle

We used  the T5 tokenizer to tokenize the data
The tokenizer uses the batch_encode_plus method to perform tokenization
