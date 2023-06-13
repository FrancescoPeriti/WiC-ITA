# The Time-Embedding Travelers@WiC-ITA
This repository contains the code accompanying the paper titled "The Time-Embedding Travelers@WiC-ITA". The paper presents the results of our participation in the WiC-ITA 2023 shared task.

### WiC-ITA 2023 Shared Task
[WiC-ITA](https://wic-ita.github.io/) is the first Word-in-Context task for Italian, organized as part of [EVALITA 2023](https://www.evalita.it/campaigns/evalita-2023/), the 8th evaluation campaign for Natural Language Processing and Speech tools for Italian. The event took place in Parma, Italy, from September 7th to 8th, 2023, and was organized by the Italian Association for Computational Linguistics ([AILC](https://www.ai-lc.it/en/)). 

### Paper Abstract
The WiC-ITA shared task aims to determine whether a word appearing in two distinct sentences carries the same meaning. The task consists of two subtasks: binary classification <b>(Subtask 1)</b> and ranking <b>(Subtask 2)</b>. Each subtask is designed in both a monolingual (Italian) and multilingual (Italian-English) setting. In this report, we present the results of our participation in WiC-ITA. In our experiments, we leverage the condition number of the cosine similarity matrix between XLM-R
embeddings and demonstrate competitive performance, ranking among the top positions in both the monolingual and cross-lingual setting. Our results indicate that
semantic information is present not only in the last layers but also across the middle layers of XLM-R and throughout the entire architecture. This suggests potential avenues for future research to explore the use of the complete set of embeddings, rather than solely relying on the embeddings extracted from the last layer(s).

### Data
The dataset used for development and evaluation phase is directly available in the following repository: https://github.com/wic-ita/data. Please refer to this repository to access the data.

### Contents
This repository includes the following files:

`extraction.py`: A Python class to extract word embeddings from a BERT model.

`wicita.ipynb`: The jupyter notebook containing the implementation of our approach.
