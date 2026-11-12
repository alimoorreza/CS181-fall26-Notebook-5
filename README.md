# CS181-Fall26-Notebook-5
## Underwater Animal Semantic Segmentation:
<b>Due</b>: Thursday, November 19th, 2026

For this assignment, you'll use the final part of Underwater Animal Detection Dataset (UWS_sem_seg_v1), which can be downloaded from [here](https://drive.google.com/uc?id=155Vg3iOTK3aed11LXC2lFQBxhdimfuZB). This is a multiclass semantic segmentation task where you predict pixel labels from predefined categories of underwater animals (starfish, shark, whale) and background elements (rock, water, etc.). You'll train and test using the state-of-the-art HRNet (High Resolution Network).
![Underwater Animal Categories](https://github.com/alimoorreza/CS181-Fall26-Notebook-3/blob/main/etc/uws_v1_samples.png)


## Notebook:
It's an assignment divided into three parts. You should use these three notebooks for the corresponding experiments:
   - [_Part 1: Notebook_5_starter for HRNet trainining using UWSv1 dataset_](https://github.com/alimoorreza/CS181-Fall26-Notebook-5/blob/main/cs181_part1_training_HRNet_model.ipynb).
   - [_Part 2: Notebook_5_starter for HRNet inference using UWSv1 dataset_](https://github.com/alimoorreza/CS181-Fall26-Notebook-5/blob/main/cs181_part2_inference_using_trained_HRNet.ipynb).

## Expectations: ☑️
You need to create a Colab notebook starting from here - [_Part 1: Notebook_5_starter for HRNet trainining using UWSv1 dataset_](https://github.com/alimoorreza/CS181-Fall26-Notebook-5/blob/main/cs181_part1_training_HRNet_model.ipynb). After training HRNet model using UWSv1 dataset, you need to evaluate the trained model using 10 sample images (randomly selected) using the third notebook [_Part 2: Notebook_5_starter for HRNet inference using UWSv1 dataset_](https://github.com/alimoorreza/CS181-Fall26-Notebook-5/blob/main/cs181_part2_inference_using_trained_HRNet.ipynb)
Add your code and results to document your experiment.



### Rubric:
> *This assignment is worth 7 points. It will be graded using the following rubric. I strongly suggest evaluating your project using this rubric before turning it in. It consists of two criteria: 1) *writing, and 2) *code. The details of the rubrics are as follows:

| Exercise #  | Points Awarded (out of 7)  | Notes |
| --------- | ------------------- | --------- |
| 1: HRNet training using UWSv1 dataset (train split)              |    -/3.0    |            |
| 2: HRNet inference using UWSv1 dataset (validation split)        |    -/4.0    |            |
| <b>Total                                                         |    -/7.0   |     </b>   |

