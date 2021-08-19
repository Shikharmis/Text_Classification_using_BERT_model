# Text_Classification_using_BERT_model
About BERT:
BERT is a model that broke several records for how well models can handle language-based tasks, it is trained on wikipedia. BERT is basically a trained Transformer Encoder stack. CLS here stands for Classification.

It can be used for multple problems like:-

Sentence Classification: we look for only first position i.e. CLS token ID
Sentiment analysis
Fact-checking
BERT doesn’t look at words as tokens. Rather, it looks at WordPieces. tokenization.py is the tokenizer that would turns your words into wordPieces appropriate for BERT.
