# WHiC

* This repository contains the CONTEXT-WN dataset described in the \*SEM 2017 Paper, [Detecting Asymmetric Semantic Relations in
Context : A Case Study on Hypernymy Detection](http://cs.umd.edu/~yogarshi/papers/2017/starsem2017.pdf).

* The data has been split into a train, dev, and test set. The same split has been used in the experiments reported in the paper.

* The data is in a tab seperated format with 4 columns. Each row is a single example of the type (c_l,w_l,c_r,w_r)  with the columns as follows :

    1) c_l = left context
    2) w_l = left word
    3) c_r = right context
    4) w_r = right word
    5) Entailment label - 0 = False, 1 = True

* The data is already tokenized and lowercased 

* If you use the data, please cite the paper 

        @InProceedings{VyasCarpuat2017,
                Title = {Detecting Asymmetric Semantic Relations in Context : A Case Study on Hypernymy Detection},
                Booktitle = {Proceedings of *SEM 2017},
                Author = {Vyas, Yogarshi and Carpuat, Marine},
                Year = {2017},
                Location = {Vancouver, Canada}
        }
