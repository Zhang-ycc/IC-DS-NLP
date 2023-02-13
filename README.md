# Project-NLP
NLP project for Imperial DS Winter School

## Structure
```
.
├── README.md
├── data
│         └── document_parses
├── pre_data
│         ├── dataset0.pkl
│         ├── filteredOntos.pkl
│         └── finalBPETokenizer15757ForBiomedicine.json
├── output
│         ├── Track-3-2-model
│         ├── Track-4-1
│         ├── Track-4-2
│         └── Track-5
└── nlp_project.ipynb
```


## Install
```
conda create -n ic_ds_nlp python=3.9
activate ic_ds_nlp
pip install tqdm
pip install tokenizers
pip install gensim
pip install nltk
pip install transformers
pip install torch
pip install joblib
pip install sklearn
pip install matplotlib
pip install mpld3
pip install py2neo
```

## Additional Instructions

### Track 2.2
```
nltk.download('all')
```
Install **NLTK** using this cell. Only need to run for one time.
If failed, download the NLTK manually on https://www.nltk.org.

### Part 5
To run this part, install and configure **Neo4j** first. The 
official website of Neo4j: https://neo4j.com

### Pre-data
Not committed due to too large data 