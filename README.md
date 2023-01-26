# Formality Scores for CodE Alltag

This repository contains formality annotations for each word, sentence and document in CodE Alltag, a German-language email corpus.
Formality scores between +1 (most formal) and -1 (most informal) are obtained automatically with transformer models fine-tuned on [formality-assessed sentences](https://github.com/ee-2/in_formal_sentences) (for sentences and documents) or on [formality-assessed words](https://github.com/ee-2/I-ForGer) (for words).

The *formality\_scores\_**documents**\*.json* files provide the formality scores for each document.
The *formality\_scores\_**sentences**\*.json* and *formality\_scores\_**words**\*.json* files include a list of all formality scores for the sentences or words in each document.

The **TSV** files *sentences\_formality\_scores.tsv* and *words\_formality\_scores.tsv* list the formality score for each sentence or word in the entire corpus.
