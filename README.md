# AlbNews

This repository is a list of resources for conducting NLP (Natural Language Processing) research in Albanian language. Each resource that is linked here has already been published somewhere else. This list is not exhaustive, since new corpora or other resources are released time to time. For this reason, anyone who knows about public NLP resources of Albanian language is welcome to add them here with a pull request. 

## Data

Please download [AlbNews corpus](http://hdl.handle.net/11234/1-5411) and place its files inside the data/ folder. Afterwards, you can run the code of this repository using the following command: 

```
$ python basic_experiments.py -c <classifier>
```


## Citation

**If using the AlbNews data or the code of this repository, please cite the following paper:**

Erion Çano, Dario Lamaj. AlbNews: A Corpus of Headlines for Topic Modeling in Albanian. 
CoRR, abs/2402.04028, February 2024. URL: http://arxiv.org/abs/2402.04028.

@article{DBLP:journals/corr/abs-2402.04028, \
author = {Erion {\c{C}}ano, Dario Lamaj}, \
title = {AlbNews: A Corpus of Headlines for Topic Modeling in Albanian}, \
journal = {CoRR}, \
volume = {abs/2402.04028}, \
year = {2024}, \
url = {http://arxiv.org/abs/2402.04028 }, \
archivePrefix = {arXiv}, \
eprint = {2402.04028}, \
}