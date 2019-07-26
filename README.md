# WHiC

* This repository contains the CONTEXT-WN dataset described in the \*SEM 2017 Paper, [Detecting Asymmetric Semantic Relations in
Context : A Case Study on Hypernymy Detection](http://cs.umd.edu/~yogarshi/publications/2017/starsem2017.pdf).

* The data has been split into a train, dev, and test set. The same split has been used in the experiments reported in the paper.

* The data is in a tab seperated format with 4 columns. Each row is a single example of the type (c_l,w_l,c_r,w_r)  with the columns as follows :

    1) c_l = left context
    2) w_l = left word
    3) c_r = right context
    4) w_r = right word
    5) Entailment label - 0 = False, 1 = True

* The data is already tokenized and lowercased 

* The data is available under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license. If you use the data, please cite our paper:

    ```  
    @inproceedings{VyasCarpuat2017,
      address = {{Vancouver, Canada}},
      title = {Detecting {{Asymmetric Semantic Relations}} in {{Context}}: {{A Case}}-{{Study}} on {{Hypernymy Detection}}},
      shorttitle = {Detecting {{Asymmetric Semantic Relations}} in {{Context}}},
      booktitle = {Proceedings of the 6th {{Joint Conference}} on {{Lexical}} and {{Computational Semantics}} (*{{SEM}} 2017)},
      publisher = {{Association for Computational Linguistics}},
      doi = {10.18653/v1/S17-1004},
      author = {Vyas, Yogarshi and Carpuat, Marine},
      month = aug,
      year = {2017},
      pages = {33--43},
    }
    ```


