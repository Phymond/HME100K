# HME100K: A Dataset For Handwritten Mathematical Expression 

We introduce the HME100K dataset, a large-scale and real scene dataset suitable 
for evaluating handwritten mathematical expression recognition task.

### Image Collection

The data were collected from tens of thousands of writers who wrote the MEs on papers and uploaded them to an internet application. 

### Examples

![Examples](https://github.com/Phymond/HME100K/blob/main/examples/examples.png)


### How to download

You can download the dataset from the official website: https://ai.100tal.com/dataset

```
HME100K
    |
    |---train
    |       |---train_images
    |       |
    |       |---train_labels.txt
    |
    |---test
    |       |---test_images
    |       |
    |       |---test_labels.txt
    |
    |---subset
            |---easy.json
            |
            |---medium.json
            |
            |---hard.json

```

### Citation

If you find this dataset helpful for your research, please cite the following paper:

```
@article{yuan2022syntax,
  title={Syntax-Aware Network for Handwritten Mathematical Expression Recognition},
  author={Yuan, Ye and Liu, Xiao and Dikubab, Wondimu and Liu, Hui and Ji, Zhilong and Wu, Zhongqin and Bai, Xiang},
  journal={arXiv preprint arXiv:2203.01601},
  year={2022}
}
```
