# Repos general idea is to parse large native georgian websites for text data


## Parsed Raw Corpus is available at [Google Drive](https://drive.google.com/drive/folders/1JF2mLOvIOPJE9259H_rb097eYPS9dMs4?usp=share_link).

Data is also accessible from transformers datasets library at [huggingface](https://huggingface.co/?recent=update-dataset)

```python
from datasets import load_dataset

dataset = load_dataset("ZurabDz/geo_small_corpus")
dataset_large = load_dataset("ZurabDz/geo_large_corpus_cleaned_v2")
```