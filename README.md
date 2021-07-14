# Semantic Query Tagging Dataset

Benchmark dataset for _Semantic Query Tagging_.  
It contains a total of 6749 manually-labeled real-world unique queries in the movie domain.  
Data are formatted using the [IOB2](https://en.wikipedia.org/wiki/Inside–outside–beginning_(tagging)) labeling format.

## Task 1 - Semantic Query Tagging

_Task 1_ folder contains the dataset used in [[1](#1)].  
_Basic_, _Advanced_, and _Hard_ refers to three different scenarios of increasing difficulty built by subsetting the original query set.  
The queries come already split into _train_, _dev_, and _test_ sets following a temporal splitting approach.  
Please refer to [[1](#1)] for an in-depth description of the dataset and the related design choices.

<a name="1"></a>[[1](#1)] _Bassani et al., Semantic Query Labeling Through Synthetic Query Generation, SIGIR 2021_

## Task 2

Cooming Soon!

## Citations

Please cite the following if you use this dataset in any way:  
_Bassani et al., Semantic Query Labeling Through Synthetic Query Generation, SIGIR 2021_
```bibtex
@inproceedings{bassani2021,
    author    = {Elias Bassani and Gabriella Pasi},
    title     = {Semantic Query Labeling Through Synthetic Query Generation},
    booktitle = {Proceedings of the 44th International {ACM} {SIGIR} Conference on
                Research and Development in Information Retrieval, {SIGIR} 2021,
                Virtual Event, Canada, July 11–15, 2021},
    publisher = {{ACM}},
    year      = {2021},
    url       = {https://doi.org/10.1145/3404835.3463071},
    doi       = {10.1145/3404835.3463071},
}
```


Also, because this dataset is built using queries from the AOL Query Logs, please cite:  
_Pass et al., A Picture of Search, ICPS 2006_
```bibtex
@inproceedings{DBLP:conf/infoscale/PassCT06,
    author    = {Greg Pass and Abdur Chowdhury and Cayley Torgeson},
    editor    = {Xiaohua Jia},
    title     = {A picture of search},
    booktitle = {Proceedings of the 1st International Conference on Scalable
                Information Systems, Infoscale 2006, Hong Kong, May 30-June 1,
                2006},
    publisher = {{ACM}},
    year      = {2006},
    url       = {https://doi.org/10.1145/1146847.1146848},
    doi       = {10.1145/1146847.1146848},
}
```
