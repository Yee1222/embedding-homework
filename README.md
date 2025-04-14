# 金庸小说人物关系向量化分析

本项目基于PyTorch实现了Word2Vec中的Skip-gram和CBOW模型，通过对金庸武侠小说文本进行训练，生成主要人物关系的词向量，并通过PCA降维进行可视化分析。

## 功能特性

- 📖 支持多部金庸小说联合训练
- 🔠 自定义分词词典（包含金庸全人物名称）
- 🛑 中文停用词过滤与低频词过滤
- 🤖 支持两种经典词嵌入模型：Skip-gram & CBOW
- 📊 交互式3D/2D可视化分析

## 环境依赖

- Python 3.7+
- 主要依赖库：
  ```bash
  torch >= 1.10
  jieba >= 0.42
  scikit-learn
  matplotlib
  numpy
  tqdm
