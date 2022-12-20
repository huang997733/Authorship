# Authorship
Machine Learning Authorship prediction

## Introduction
The aim of this project is to predict for each of the test papers, which of a set of 100 prolific authors were involved in writing the paper. For detailed information of this project, please see the project spec. :)

Team with Tianyu Huang https://github.com/TianyuHuang-000 and Jinjie Ding jinjied@student.unimelb.edu.au

## Dataset
### train.json
contains 25.8k papers. This file is in JSON format as a list of papers, where each paper is a dictionary with keys:
1. authors: a set of the IDs of the authors of the paper,with values in{0,...,21245}
2. year
3. venue: mapped to a unique integer value {0,...,464}
4. title: each word has been mapped to an index in {1,...,4999}
5. abstract: proceessed as above, using the same word-integer mapping

### test.json
contains 800 papers, stored in JSON format with the fields year, venue, title and abstract as described above, along with one additional item:
1. identifier: The unique identifier of the paper
2. coauthors: The IDs of the co-authors of the paper, with values in {100,...,21245}

## Approach


## Kaggle result
