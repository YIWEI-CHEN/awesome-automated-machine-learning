# Awesome Automated Machine Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome automated machine learning resources. 
Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), 
[awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), 
[awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers)
[awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search), and
[awesome-NAS](https://github.com/D-X-Y/awesome-NAS).

Please feel free to [pull requests](https://github.com/YIWEI-CHEN/awesome-automated-machine-learning/pulls) 
or [open an issue](https://github.com/YIWEI-CHEN/awesome-automated-machine-learning/issues) to add papers.
Markdown format:
```markdown
- Paper Name [[pdf]](link) [[code]](link)
  - Author 1, Author 2, Author 3. Conference Year
```


## Table of Contents
- [Automated Feature Engieerning](#automated-feature-engineering)
    - [Exploration and Reduction](#exploration-and-reduction)
    - [Reinforcement Learning](#reinforcement-learning)
- [Automated Model Selection and Learning](#automated-model-selection-and-learning)
    - [Bayesian Optimization](#bayesian-optimization)
    - [Evolutionary Algorithm](#evolutionary-algorithm)
    - [Gradient-based Optimization](#gradient-based-optimization)
- [Automated Deep Learning](#automated-deep-learning)
    - [Bayesian Optimization](#bayesian-optimization)
    - [Reinforcement Learning](#reinforcement-learning)
    - [Evolutionary Algorithm](#evolutionary-algorithm)
    - [Gradient-based Optimization](#gradient-based-optimization)
    - [Test Performance on CIFAR-10](#test-performance-on-cifar-10)
- [Survey](#survey)
- [Related Resources](#related-resources)

## Automated Feature Engineering

### Exploration and Reduction
- Deep Feature Synthesis: Towards Automating Data Science Endeavors
    [[pdf]](https://ieeexplore.ieee.org/document/7344858)
    [[code]](https://github.com/Featuretools/featuretools)
     - James Max Kanter, Kalyan Veeramachaneni. 
- ExploreKit: Automatic Feature Generation and Selection
    [[pdf]](https://ieeexplore.ieee.org/document/7837936)
    [[code]](https://github.com/giladkatz/ExploreKit)
    - Gilad Katz, Eui Chul Richard Shin, Dawn Song. ICDM 2016
   
### Reinforcement Learning
- Feature Engineering for Predictive Modeling using Reinforcement Learning
    [[pdf]](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16564/16719)
    - Udayan Khurana, Horst Samulowitz, Deepak Turaga, AAAI 2018

## Automated Model Selection and Learning

### Bayesian Optimization
- Efficient and Robust Automated Machine Learning
    [[pdf]](https://papers.nips.cc/paper/5872-efficient-and-robust-automated-machine-learning.pdf)
    [[code]](https://github.com/automl/auto-sklearn)
    - Matthias Feurer, Aaron Klein, Katharina Eggensperger, Jost Springenberg, Manuel Blum, Frank Hutter. NIPS 2015
- Auto-WEKA: Combined Selection and Hyperparameter Optimization of Classification Algorithms
    [[pdf]](http://www.cs.ubc.ca/labs/beta/Projects/autoweka/papers/autoweka.pdf)
    [[code]](https://github.com/automl/autoweka)
    - Chris Thornton, Frank Hutter, Holger H. Hoos, Kevin Leyton-Brown. KDD 2013

### Evolutionary Algorithm
- Automating Biomedical Data Science Through Tree-Based Pipeline Optimization
    [[pdf]](https://link.springer.com/chapter/10.1007/978-3-319-31204-0_9)
    [[code]](https://github.com/EpistasisLab/tpot)
    - Randal S. Olson, Ryan J. Urbanowicz, Peter C. Andrews, Nicole A. Lavender, La Creis Kidd, Jason H. Moore. 
      EvoApplications 2016

### Gradient-based Optimization
- TODO

## Automated Deep Learning

### Bayesian Optimization
- Auto-Keras: Efficient Neural Architecture Search with Network Morphism
    [[pdf]](https://arxiv.org/abs/1806.10282)
    [[code]](https://github.com/jhfjhfj1/autokeras)
    - Haifeng Jin, Qingquan Song, Xia Hu. arXiv 1806

### Reinforcement Learning
- Neural Architecture Search with Reinforcement Learning (NAS)
    [[pdf]](https://arxiv.org/abs/1611.01578)
    [[unofficial code]](https://github.com/titu1994/neural-architecture-search)
    - Barret Zoph and Quoc V. Le. ICLR 2017
- Learning Transferable Architectures for Scalable Image Recognition (NASNet)
    [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zoph_Learning_Transferable_Architectures_CVPR_2018_paper.pdf)
    [[nasnet]](https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet)
    - Barret Zoph, Vijay Vasudevan, Jonathan Shlens, Quoc V. Le. CVPR 2018
- Efficient Neural Architecture Search via Parameter Sharing (ENAS)
    [[pdf]](http://proceedings.mlr.press/v80/pham18a.html) 
    [[code]](https://github.com/melodyguan/enas)
    - Hieu Pham, Melody Y. Guan, Barret Zoph, Quoc V. Le, Jeff Dean. ICML 2018
- Path-Level Network Transformation for Efficient Architecture Search (PathLevel-EAS) 
    [[pdf]](http://proceedings.mlr.press/v80/cai18a/cai18a.pdf)
    [[code]](https://github.com/han-cai/PathLevel-EAS)
    - Han Cai, Jiacheng Yang,  Weinan Zhang, Song Han,Yong Yu. ICML 2018
    
### Evolutionary Algorithm
- Large-Scale Evolution of Image Classifiers (LargeEvoNet)
    [[pdf]](http://proceedings.mlr.press/v70/real17a)
    [[code]](https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet)
    - Esteban Real, Sherry Moore, Andrew Selle, Saurabh Saxena, Yutaka Leon Suematsu, Jie Tan, Quoc V. Le, 
      Alex Kurakin. ICML 2017
- Regularized Evolution for Image Classifier Architecture Search (AmoebaNet)
    [[pdf]](https://arxiv.org/abs/1802.01548)
    [[code]](https://github.com/tensorflow/tpu/tree/master/models/official/amoeba_net)
    - Esteban Real, Alok Aggarwal, Yanping Huang, Quoc V Le. AAAI 2019
    
### Gradient-based Optimization
- DARTS: Differentiable Architecture Search
    [[pdf]](https://openreview.net/pdf?id=S1eYHoC5FX)
    [[code]](https://github.com/quark0/darts)
    - Hanxiao Liu, Karen Simonyan, Yiming Yang. ICLR 2019
- ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware
    [[pdf]](https://openreview.net/pdf?id=HylVB3AqYm)
    [[code]](https://github.com/MIT-HAN-LAB/ProxylessNAS)
    - Han Cai, Ligeng Zhu, Song Han. ICLR 2019

### Test Performance on CIFAR-10
(Warning: The following values are directly chosen from their papers. Their testing environments might be different and unfair, so some of comparison might be meaningless. Please take the risk on your own.)

|    Model   | Error (%) | GPU days | Params (Million) | Method |
| ---------- | --------- | ------- | ---------------- | -------- |
| [DensNet-BC](http://openaccess.thecvf.com/content_cvpr_2017/papers/Huang_Densely_Connected_Convolutional_CVPR_2017_paper.pdf) | 3.46      | - | 25.6 | manual |
| [PyramidNet+SD](https://arxiv.org/abs/1802.02375) | 2.31 | - | 26 | manual |
| [Auto-Keras](https://arxiv.org/abs/1806.10282) | 3.6 | 0.5 | - | Bayesian |
| [NAS](https://arxiv.org/abs/1611.01578) | 3.65 | 16,800 - 22,400 | 37.4 | reinforcement |
| [NASNet-A](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zoph_Learning_Transferable_Architectures_CVPR_2018_paper.pdf) | 2.40 | 1,350 - 1,800 | 27.6 | reinforcement |
| [ENAS](http://proceedings.mlr.press/v80/pham18a.html) | 2.89 | **0.45** | 4.6 | reinforcement |
| [PathLevel EAS](http://proceedings.mlr.press/v80/cai18a/cai18a.pdf) | 2.3 | 8.33  | 14.3 | reinforcement |
| [LargeEvoNet](http://proceedings.mlr.press/v70/real17a) | 5.4 | ? | 5.4 | evolutionary |
| [AmoebaNet-B*](https://arxiv.org/abs/1802.01548v2) | 2.13 | 3150 | 34.9 | evolutionary |
| [DARTS](https://openreview.net/pdf?id=S1eYHoC5FX) | 2.76 | 4 | **3.3** | gradient-based |
| [Proxyless-G](https://openreview.net/pdf?id=HylVB3AqYm) | **2.08** | ? | 5.7 | gradient-based |
 
 \* The best result only appears in the arXiv v2.
## Survey
- Neural Architecture Search: A Survey [[pdf]](https://arxiv.org/abs/1808.05377)
    - Thomas Elsken, Jan Hendrik Metzen, Frank Hutter. arXiv 1808
- Taking Human out of Learning Applications: A Survey on Automated Machine Learning 
    [[pdf]](https://arxiv.org/abs/1810.13306)
    - Yao Quanming, Wang Mengshuo, Jair Escalante Hugo, Guyon Isabelle, Hu Yi-Qi, Li Yu-Feng, Tu Wei-Wei, Yang Qiang, 
      Yu Yang. arXiv 1810

## Related Resources
- [hibayesian/awesome-automl-papers](https://github.com/hibayesian/awesome-automl-papers)
- [markdtw/awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search)
- [AutoML.org/Literature on Neural Architecture Search](https://www.ml4aad.org/automl/literature-on-neural-architecture-search/)
- [D-X-Y/awesome-NAS](https://github.com/D-X-Y/awesome-NAS)
- [weiaicunzai/awesome-image-classification](https://github.com/weiaicunzai/awesome-image-classification)
- [ChanChiChoi/awesome-automl](https://github.com/ChanChiChoi/awesome-automl)
- [songzhaozhe/Model-Architecture-Search-Paper-List](https://github.com/songzhaozhe/Model-Architecture-Search-Paper-List)
