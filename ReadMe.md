# 动手学深度学习-学习代码

### 简介
主要存放学习动手学深度学习过程中的代码

### 书籍网址

https://zh-v2.d2l.ai/


### d2l目录
1. 安装d2l包
```bash
pip install d2l
```
2. d2l目录存放不同框架下的d2l包源代码

使用方法：

```python
from d2l import 框架名 as d2l
```

在这一段代码前加入以下代码即可引用d2l包

```python
import sys
sys.path.append('../..')
```


### 引用

```
@article{zhang2021dive,
    title={Dive into Deep Learning},
    author={Zhang, Aston and Lipton, Zachary C. and Li, Mu and Smola, Alexander J.},
    journal={arXiv preprint arXiv:2106.11342},
    year={2021}
}
```

Mindspore部分代码来源于：
```
https://github.com/lvyufeng/d2l-mindspore
```
