# MNIST 手写数字分类实践

这本是一个要求使用**飞桨AI studio**在线完成的**人工智能引论**课程作业。

由于直接使用**飞桨AI studio**里的`经典 mnist 数据集`会出各种依赖和其他奇怪的问题，为了作业的**健壮性**，我本地也跑了一遍相同的过程。这个仓库就是本地跑的那一遍完整作业内容。

## 环境

可以手动创建一个 conda 环境后安装依赖：

```powershell
conda create -n task3_mnist python=3.10 -y
conda activate task3_mnist
pip install -r requirements.txt
```

## 数据说明

mnist 原始数据文件已经放在仓库的 `data/data65/` 目录下。因此，在 `main.ipynb` 中的数据路径被相应的更改了：

```python
mnist_path = 'data/data65/'
```

## 文件说明

- `main.ipynb`：作业主文件，共 3 个代码 cell。
- `requirements.txt`：Python 依赖。
- `data/data65/`：MNIST 原始压缩数据文件。
