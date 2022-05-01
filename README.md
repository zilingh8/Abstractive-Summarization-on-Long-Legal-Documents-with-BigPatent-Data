# Abstractive-Summarization-on-Long-Legal-Documents-with-BigPatent-Data


In this Natural Language Processing school project, I work on summarization of long legal documents on the Big Patent Dataset. 
There are two types of summarization abstractive versus extractive. Extractive summarization simply extracts important phrases or sentences. On the other hand, abstractive summarization requires 'understanding' of meaning to generate novel summaries of the original text. 

The BigPatent dataset was assembled for abstractive summarization and this project focuses on exploring if the quality of abstractive summaries can be improved by using extractive techniques like TFIDF, cosine similarity before passing on to a T5 model for abstractive summarization.
The baseline model for comparison is the SOTA Big Bird Pegasus model which excels at abstractive summarization on long documents.

Evaluation of performance was done using Rouge-1, 2, L and QuestEval.

For discussion and access to view my code in google colaboratory, please private message me on linkedin.

Code:
- Data Extraction from Big Patent Dataset
- T5 only 
- TFIDF-T5
- TFIDF-Cosine Similarity-T5
- BigBird Pegasus

You will find my slide deck and paper in this repo.
