# PairCNN-Ranking
A tensorflow implementation of [Learning to Rank Short Text Pairs with Convolutional Deep Neural Networks](http://disi.unitn.it/~severyn/papers/sigir-2015-long.pdf)

## Training Data
As **train.txt** and **test.txt** in **./data** dir, each line is an sample, which is splited by comma: query, document, label. And the example data is created by me to test the code, which is not real click data.

## Usage
```bash
python train.py -h
```


需要使用python2.7
tensorflow使用0.12版本
只能在liunx下运行，windows上没有tensorflow这个包

ubuntu上pip的安装参考：

https://zhuanlan.zhihu.com/p/137114974
