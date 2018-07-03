# Semantic segmentation

## Description

Semantic segmentation is a dense prediction task that sets a goal of predicting
a class label for every pixel of an input image. Generally, the objective of a
segmentation algorithm is to compute a label map with the spatial resolution
equal to the input.

Usual evaluation metrics are:

* Linear Correlation Coefficient(LCC): LCC is a measure of the linear correlation between the
ground truth and the predicted quality scores
* Spearman Rank Order Correlation Coefficient (SROCC): The SROCC measures the monotonic
relationship between ground-truth and estimation

*refer here(https://arxiv.org/pdf/1707.08347.pdf)


## Results


### LIVE — Testing set

[Dataset description](datasets/pascal_voc_2012_segmentation.md)

| Model | LCC | SROCC | Weights | Paper | Code |
|:------|:-----|:-----|:--------|:------|:-----|
| VGG-16                | 0.973 | 0.974 |  [model](https://github.com/xialeiliu/RankIQA/blob/master/pre-trained)|[paper](https://arxiv.org/pdf/1707.08347.pdf) | [Caffe](https://github.com/xialeiliu/RankIQA) |


### TID 2013 — Testing set

[Dataset description](datasets/pascal_voc_2012_segmentation.md)

| Model | LCC | SROCC | Weights | Paper | Code |
|:------|:-----|:-----|:--------|:------|:-----|
| VGG-16                | NA | 0.780 |  [model](https://github.com/xialeiliu/RankIQA/blob/master/pre-trained)|[paper](https://arxiv.org/pdf/1707.08347.pdf) | [Caffe](https://github.com/xialeiliu/RankIQA) |
