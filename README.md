# CVAE-CLIP Project

## Overview
This project contains code for training and evaluating a Conditional Variational Autoencoder (CVAE) model on the CelebA dataset. The primary goal is to generate images conditioned on specific attributes using the CVAE model.

## Environment Setup and Dependencies
To set up the environment and install the required dependencies, follow these steps:
Clone the repository:
   ```bash
   git clone https://github.com/laowangshini/CVAE-CLIP.git
   cd CVAE-CLIP
   ```

## Repository Structure
The repository contains the following files and directories:

- `realtest2_clipcvae.ipynb`: Jupyter notebook for training and evaluating the CVAE model on the CelebA dataset.
- `realtest2_cvae.ipynb`: Jupyter notebook for training and evaluating the CLIP + CVAE model on the CelebA dataset.


## 你可以通过Kaggle下载CelebA数据集。以下是CelebA数据集的Kaggle下载链接：

[**CelebA Dataset on Kaggle**](https://www.kaggle.com/datasets/jessicali9530/celeba-dataset)

### 下载步骤：
1. 点击链接访问数据集页面。
2. 如果你还没有登录Kaggle账户，先登录你的账户。
3. 在页面上点击“Download”按钮下载数据集压缩包。

下载后，你可以解压文件，得到数据集的图像和标签文件。

### 注意：
你可能需要安装并配置Kaggle的API才能通过命令行进行下载。可以使用以下命令：

```bash
kaggle datasets download -d jessicali9530/celeba-dataset
```

确保你的Kaggle API密钥已经设置在环境变量中，具体的配置方法可以参考[Kaggle API文档](https://www.kaggle.com/docs/api)。
