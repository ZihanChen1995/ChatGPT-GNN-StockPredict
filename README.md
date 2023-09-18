# 📈 (Dataset Available) -- ChatGPT Informed Graph Neural Network for Stock Movement Prediction 📈

- This repository houses the datasets/resources used in our paper [ChatGPT Informed Graph Neural Network for Stock Movement Prediction](https://arxiv.org/abs/2306.03763). 
- This research introduces a novel framework that leverages ChatGPT's graph inference capabilities to enhance Graph Neural Networks (GNN).
- Our model shows superior performance in both (1) stock movement prediction and (2) portfolio construction.
- Dive in to find the datasets, code samples, and more!
- 📄 Paper: [[Link to the paper]](https://arxiv.org/abs/2306.03763)

## 🚀 Get Started

The data can be found in the Data folder, which contains two files:

- `ticker_train_data.json`: This file holds the data utilized for training and validation of our model.
- `ticker_test_data.json`: This file contains the data used for model evaluation.

To load the data, you can start with 4 lines of code:
```
import pandas as pd
import json

train_data = pd.read_json('./Data/ticker_train_data.json')
test_data = pd.read_json('./Data/ticker_test_data.json')
```

The `Affected Companies` column provides two key insights:

- Companies that ChatGPT predicts will be influenced by the financial news.
- The sentiment indicating the nature of the impact on these companies (e.g., positive or negative).

For a deeper exploration of the data, please feel free to check the `data_checking.ipynb`.


## 🔗 Citation:

We encourage collaboration and use of this dataset for further advancements in stock prediction using deep learning. If you find this resource useful, kindly cite our paper. Happy researching!

```
@article{chen2023chatgpt,
  title={ChatGPT Informed Graph Neural Network for Stock Movement Prediction},
  author={Chen, Zihan and Zheng, Lei Nico and Lu, Cheng and Yuan, Jialu and Zhu, Di},
  journal={arXiv preprint arXiv:2306.03763},
  year={2023}
}
```
