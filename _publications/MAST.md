---
title: "Multi-Aspect Streaming Tensor Completion"
collection: publications
permalink: /publications/MAST
venue: "The 23rd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining. (KDD' 2017)"
date: 2017-8-16
citation: '<b>Qingquan Song</b>, Xiao Huang, Hancheng Ge, Jame Caverlee, and Xia Hu. <i>The 23rd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining.</i>. <b>KDD 2017</b>.'

<!-- ## Cite this work

Biblatex entry:

    @online{jin2018efficient,
      author       = {Qingquan Song and Xiao Huang and Hancheng Ge and James Caverlee and Xia Hu},
      title        = {Multi-Aspect Streaming Tensor Completion},
      date         = {2017-08-16},
      year         = {2017},
      eprintclass  = {cs.LG},
      eprinttype   = {arXiv},
      eprint       = {cs.LG/1806.10282},
    }
 -->

---
[[Paper]](http://song3134.github.io/files/Qingquan_KDD17.pdf) 
<!-- [[Code]](https://github.com/song3134/MAST)  -->


## Abstract
Tensor completion has become an effective computational tool in many real-world data-driven applications. Beyond traditional static setting, with the increasing popularity of high velocity streaming data, it requires efficient online processing without reconstructing the whole model from scratch. Existing work on streaming tensor completion is usually built upon the assumption that tensors only grow in one mode. Unfortunately, the assumption does not hold in many real-world situations in which tensors may grow in multiple modes, i.e., multi-aspect streaming tensors. Efficiently modeling and completing these incremental tensors without sacrificing its effectiveness remains a challenging task due to the uncertainty of tensor mode changes and complex data structure of multi-aspect streaming tensors. To bridge this gap, we propose a Multi-Aspect Streaming Tensor completion framework (MAST) based on CAN- DECOMP/PARAFAC (CP) decomposition to track the subspace of general incremental tensors for completion. In addition, we inves- tigate a special situation where time is one mode of the tensors, and leverage its extra structure information to improve the general framework towards higher effectiveness. Experimental results on four datasets collected from various real-world applications demon- strate the effectiveness and efficiency of the proposed framework.
