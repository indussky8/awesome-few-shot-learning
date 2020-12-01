# Few-Shot Learning

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources including papers, comparitive results on standard datasets and relevant links pertaining to few-shot learning.  

## Contributing

Contributions are welcome. If you have suggestions for new sections or valuable works to be included, please feel free to raise an issue and discuss in [issue](https://github.com/indussky8/awesome-few-shot-learning/issues) module.

## Table of Contents
+ [Papers](#Papers)
+ [Datasets](#Datasets)
+ [Starter code for FSL](#Starter-Code)
+ [Other Resources](#Other-resources)


## Few-Shot Learning (Classification)

### Papers

#### ECCV 2020 
+ **MABAS**: Jaekyeom Kim, Hyoungseok Kim, and Gunhee Kim. "Model-Agnostic Boundary-Adversarial Sampling for Test-Time Generalization in Few-Shot learning." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460579.pdf) [[code]](https://github.com/jaekyeom/MABAS).

  <img src="readme/MABAS.png" width="500"/>
   
+ **TAFSSL**: Moshe Lichtenstein, Prasanna Sattigeri, Rogerio Feris, Raja Giryes, and Leonid Karlinsky. "TAFSSL: Task-Adaptive Feature Sub-Space Learning for few-shot classification." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520511.pdf). <b><font color="#FF3030">`<Semi-supervised>`<b><font color="#FF3030">`<transductive>`

  <img src="readme/TAFSSL.png" width="500"/>
  

   
+ **centroid alignment**: Arman Afrasiyabi, Jean-François Lalonde, and Christian Gagné. "Associative Alignment for Few-shot Image Classification." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500018.pdf) [[code]](https://lvsn.github.io/associative-alignment/).

   <img src="readme/centroid alignment.png" width="500"/>
  
+ **SSL-FSL**: Jong-Chyi Su, Subhransu Maji, and Bharath Hariharan. "When Does Self-supervision Improve Few-shot Learning?." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520630.pdf). <b><font color="#FF3030">`<self-supervised>`

  <img src="readme/SSL-FSL.png" width="500"/>
  
+ **IDA**: Qing Liu, Orchid Majumder, Alessandro Achille, Avinash Ravichandran, Rahul Bhotika, and Stefano Soatto. "Incremental Few-Shot Meta-Learning via Indirect Discriminant Alignment." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520664.pdf). <b><font color="#FF3030">`<Incremental>`

  <img src="readme/IDA.png" width="500"/>
  
+ **LS-FSL**: Shuo Wang, Jun Yue, Jianzhuang Liu, Qi Tian, and Meng Wang. "Large-Scale Few-Shot Learning via Multi-Modal Knowledge Discovery." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123550715.pdf).

  <img src="readme/LS-FSL.png" width="500"/>
  
+ **SUR**: Nikita Dvornik, Cordelia Schmid, and Julien Mairal. "Selecting Relevant Features from a Multi-domain Representation for Few-shot Classification." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123550766.pdf) [[code]](https://github.com/dvornikita/SUR). <b><font color="#FF3030">`<Meta-Dataset>`

  <img src="readme/SUR.png" width="500"/>

+ **LR-distill**: Yonglong Tian, Yue Wang, Dilip Krishnan, Joshua B. Tenenbaum, and Phillip Isola. "Rethinking Few-shot Image Classification: A Good Embedding is All You Need?." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590256.pdf) [[code]](https://github.com/WangYueFt/rfs/). <b><font color="#FF3030">`<self-supervised>` <b><font color="#FF3030">`<Meta-Dataset>`

  <img src="readme/LR-distill.png" width="500"/>
  
+ **E<sup>3</sup>BM**: Yaoyao Liu, Bernt Schiele, and Qianru Sun. "An Ensemble of Epoch-wise Empirical Bayes for Few-shot Learning." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123610392.pdf) [[code]](https://gitlab.mpi-klsb.mpg.de/yaoyaoliu/e3bm). <b><font color="#FF3030">`<transductive and inductive>`

  <img src="readme/E3BM.png" width="500"/>
  
+ **Data Design**: Othman Sbai, Camille Couprie, and Mathieu Aubry. "Impact of base dataset design on few-shot image classification." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123610579.pdf) [[code]](http://imagine.enpc.fr/~sbaio/publications/fewshot_dataset_design/index.html). <b><font color="#FF3030">`<base training set selection>`

  <img src="readme/Data Design.png" width="500"/>
  
+ **SEN**: Van Nhan Nguyen, Sigurd Løkse, Kristoffer Wickstrøm, Michael Kampffmeyer, Davide Roverso, and Robert Jenssen. "SEN: A Novel Feature Normalization Dissimilarity Measure for Prototypical Few-Shot Learning Networks." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680120.pdf). 

  <img src="readme/SEN.png" width="500"/>
  
+ **EPNet**: Pau Rodríguez, Issam Laradji, Alexandre Drouin, and Alexandre Lacoste. "Embedding Propagation: Smoother Manifold for Few-Shot Classification." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710120.pdf) [[code]](https://github.com/ElementAI/embedding-propagation). <b><font color="#FF3030">`<Semi-supervised>`<b><font color="#FF3030">`<transductive>`

  <img src="readme/EPNet.png" width="500"/>
  
+ **BSCD-FSL**: Yunhui Guo, Noel C. Codella, Leonid Karlinsky, and James V. Codella, John R. Smith, Kate Saenko, Tajana Rosing, Rogerio Feris. "A Broader Study of Cross-Domain Few-Shot Learning." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123720120.pdf) [[code]](https://github.com/IBM/cdfsl-benchmark). <b><font color="#FF3030">`<transductive and inductive>`

  <img src="readme/BSCD-FSL.png" width="500"/>
  
+ **DeepCaps-FSL**: Fangyu Wu, Jeremy S.Smith, Wenjin Lu, Chaoyi Pang, and Bailing Zhang. "Attentive Prototype Few-shot Learning with Capsule Network-based Embedding." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730239.pdf). <b><font color="#FF3030">`<transductive>`

  <img src="readme/DeepCaps-FSL.png" width="500"/>
  
+ **Neg-Cosine**: Bin Liu, Yue Cao, Yutong Lin, Qi Li, Zheng Zhang, Mingsheng Long, and Han Hu. "Negative Margin Matters: Understanding Margin in Few-shot Classification." ECCV (2020). [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490426.pdf) [[code]](https://github.com/bl0/negative-margin.few-shot.).

  <img src="readme/Neg-Cosine.png" width="500"/>
  

#### ICLR 2020





### Datasets


### Starter Code



## Other resources


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
