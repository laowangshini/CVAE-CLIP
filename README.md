# CVAE-CLIP 项目

## 概述

本项目包含使用Conditional Variational Autoencoder (CVAE) 模型在CelebA数据集上进行训练和评估的代码。主要目标是使用CVAE模型生成基于特定属性的图像，并进行相关的分析。

## 环境设置和依赖

请按照以下步骤设置环境并安装所需的依赖：

克隆仓库：
```bash
git clone https://github.com/laowangshini/CVAE-CLIP.git
cd CVAE-CLIP
```

安装依赖：您可能需要安装PyTorch, torchvision, matplotlib, numpy, Pillow以及可能的ptflops库。具体的依赖可能在Jupyter notebook文件中指定或使用。

## 仓库结构

仓库包含以下主要文件和目录：

*   `preprocess_clip_embeddings.ipynb`：利用CLIP生成嵌入
*   `text_to_image_embedder.ipynb`：映射网络的训练
*   `CVAE_renyi_divergence.ipynb`: CVAE-CLIP (KL) 的训练
*   `CVAE_renyi_divergence.ipynb`: CVAE (Rényi) 的训练
*   `Whole_tests.ipynb`：多个测试
*   `new_xiaorong.ipynb`：消融实验
*   `clip_embeddings/`：可能包含预计算的CLIP文本和图像嵌入文件的目录。
*   `model_checkpoints/`：可能包含训练好的模型检查点文件的目录。


## 数据集下载

您可以从Kaggle下载CelebA数据集。以下是CelebA数据集的Kaggle下载链接：

[**CelebA Dataset on Kaggle**](https://www.kaggle.com/datasets/jessicali9530/celeba-dataset)

### 下载步骤：
1. 点击链接访问数据集页面。
2. 如果您还没有登录Kaggle账户，先登录您的账户。
3. 在页面上点击"Download"按钮下载数据集压缩包。

下载后，您可以解压文件，得到数据集的图像和标签文件。

### 注意：

您可能需要安装并配置Kaggle的API才能通过命令行进行下载。可以使用以下命令：

```bash
kaggle datasets download -d jessicali9530/celeba-dataset
```

确保您的Kaggle API密钥已经设置在环境变量中，具体的配置方法可以参考[Kaggle API文档](https://www.kaggle.com/docs/api)。

---

您也可以使用MS COCO数据集。以下是MS COCO 2017数据集的Kaggle下载链接：

[**MS COCO 2017 Dataset on Kaggle**](https://www.kaggle.com/datasets/sabahesaraki/2017-2017)

具体的下载和使用方法请参考该数据集页面或相关文档。
