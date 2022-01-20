# Dynamic-Graph-Embedding-Methods-Summary

动态图嵌入方法学习，相关论文和代码仓库整理。
## 综述
| paper|  会议/期刊 | 
|:-:|:-:|
| [Foundations and Modeling of Dynamic Networks Using Dynamic Graph Neural Networks: A Survey](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9439502) | IEEE Access'21 | 
| [A Survey on Embedding Dynamic Graphs](https://arxiv.org/pdf/2101.01229.pdf) | arxiv'21 | 
| [Representation Learning for Dynamic Graphs: A Survey](https://www.jmlr.org/papers/volume21/19-447/19-447.pdf) | JMLR'20 | 

## Slides

| paper |  会议/期刊 | 
|:-:|:-:|
| [Dynamic Graph Representation Learning](http://web.cs.ucla.edu/~patricia.xiao/files/Paper_Reading_Group_20201006.pdf) | UCLA paper reading group'20 | 

## 模型
### 离散型

| paper| model | code | 会议 | 细分 |
|:-:|:-:|:-:|:-:|:-:|
| [DySAT: Deep Neural Representation Learning on Dynamic Graphs via Self-Attention Networks](http://yhwu.me/publications/dysat_wsdm20.pdf) | DySAT | [https://github.com/aravindsankar28/DySAT](https://github.com/aravindsankar28/DySAT) | WSDM'20 | stacked-DGNN |
| [EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs](https://jiechenjiechen.github.io/pub/evolvegcn.pdf) | EvolveGCN | [https://github.com/IBM/EvolveGCN.](https://github.com/IBM/EvolveGCN) | AAAI'20 | Integrated-DGNN |


### 连续型

| paper| model | code | 会议 | 细分 |
|:-:|:-:|:-:|:-:|:-:|
| [Predicting Dynamic Embedding Trajectory in Temporal Interaction Networks](https://cs.stanford.edu/~srijan/pubs/jodie-kdd2019.pdf) | JODIE | [https://github.com/srijankr/jodie](https://github.com/srijankr/jodie) | KDD'19 | RNN-based |
| [DYREP: LEARNING REPRESENTATIONS OVER DYNAMIC GRAPHS](https://par.nsf.gov/servlets/purl/10099025) | DyREP | [https://github.com/uoguelph-mlrg/LDG (unofficial)](https://github.com/uoguelph-mlrg/LDG) [https://github.com/Harryi0/dyrep_torch (unofficial)](https://github.com/Harryi0/dyrep_torch) | ICLR'19 | TTP-based |
| [INDUCTIVE REPRESENTATION LEARNING ON TEMPORAL GRAPHS](http://yhwu.me/publications/dysat_wsdm20.pdf) | TGAT | [https://github.com/StatsDLMathsRecomSys/Inductive-representation-learning-on-temporal-graphs](https://github.com/StatsDLMathsRecomSys/Inductive-representation-learning-on-temporal-graphs) | ICLR'20 | time embedding |
| [TEMPORAL GRAPH NETWORKS FOR DEEP LEARNING ON DYNAMIC GRAPHS](https://arxiv.org/pdf/2006.10637.pdf) | TGN | [https://github.com/twitter-research/tgn](https://github.com/twitter-research/tgn) [https://github.com/dmlc/dgl/tree/master/examples/pytorch/tgn (DGL)](https://github.com/dmlc/dgl/tree/master/examples/pytorch/tgn) | ICML'20-workshop | time embedding |

## 框架
| paper| 框架 | code | docs |
|:-:|:-:|:-:|:-:|
| [PyTorch Geometric Temporal: Spatiotemporal Signal Processing with Neural Machine Learning Models](https://dl.acm.org/doi/pdf/10.1145/3459637.3482014) | PyTorch Geometric Temporal | [https://github.com/benedekrozemberczki/pytorch_geometric_temporal](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) | [https://pytorch-geometric-temporal.readthedocs.io/en/latest/index.html](https://pytorch-geometric-temporal.readthedocs.io/en/latest/index.html)  |