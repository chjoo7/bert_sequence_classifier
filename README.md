# Document Classification Using KR-SBERT via Transformers

- Check the accuracy of model to apply our pre-trained KoRean S-BERT model to a document classification task, using HuggingFace's transformers library.


## Installation

clone and install the git repository:

```bash
git clone https://github.com/chjoo7/bert_sequence_classifier.git
```


## Models

Huggingface sentence-transformers 

sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2

## Data

BalancedNewsCorpus data 9000 train 1800 test 
We concatenated all the train News articles into one documents and split this document into 500 token size X 1140 records documents.