# On Measuring the Intrinsic Few-Shot Hardness of Datasets
This is the github repo for EMNLP 2022 paper "On Measuring the Intrinsic Few-Shot Hardness of Datasets".

## Dependency

Python 3.7, pandas, sklearn, scipy, matplotlib, seaborn

## Introduction
This repo contains the code to reproduce the results in paper from our results on various few-shot adaptation methods and hardness metrics.

## Data Format

**heatmap_raw_data.json**: Bundled datasets of model performance and raw metric scores. The key: values are:

| Key | Value | 
| :---: | :---: | 
| output_collection | the output of each method on each task with roberta as the backbone |
| majority_collection | the majority baseline of each task |
| testsize_collection | the test data size of each task |
| all_dist_collection | the distance collection between each test example to the support set of each task |
| output_collection_electra | the output of each method and each task with electra as the backbone |

## Todo
Link to the blog post.

## Citation
to appear

## Others
If you have any other questions about this repo or any idea about few-shot learning to discuss, you are welcome to open an issue or send me an [email](mailto:xzhaoar@stanford.edu), I will respond to that as soon as possible.