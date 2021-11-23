---
layout: cv
title: Fangkai Jiao
email:
  url: mailto:jiaofangkai@hotmail.com
  text: jiaofangkai@hotmail.com
homepage:
  url: http://sparkjiao.github.io
  text: sparkjiao.github.io
phone: +86 178 6415 4896
---

# Fangkai JIAO

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## **Education**

### Shandong University `2019.9 - 2022.6 (expected)`

```
GPA: 90.12/100
```

- M.Sc. in Computer Science and Technology, supervised by Prof. [Liqiang Nie](https://liqiangnie.github.io/)

### Shandong University `2015.9 - 2019.6`

```
GPA: 85.03/100
```

- B.E. in Software Engineering

## **Research Interests**

- Question answering and machine reasoning
- Pre-training for natural language understanding

## **Publications**
<font size=2>* means equal contribution.</font>
<!-- ##### \* means equal contribution. -->

### **REPT: Bridging Language Models and Machine Reading Comprehension via Retrieval-Based Pre-training**
**Fangkai Jiao**, Yangyang Guo, Yilin Niu, Feng Ji, Feng-Lin Li, Liqiang Nie. _Findings of ACL 2021._
[[pdf](https://arxiv.org/pdf/2105.04201.pdf)]
[[code](https://github.com/SparkJiao/Retrieval-based-Pre-training-for-Machine-Reading-Comprehension)]  
* The motivation of this work is to alleviate the data hungry problem of machinea reading comprehension system.   
* We propose a retrieval-based pre-training method, including two pretext tasks, namely surrounding sentences prediction and retrieval-based masked language modeling, to augment the pre-trained language models with the ability of evidence extraction.   
<!-- - Our pre-training method has achieved substantial improvements over strong baselines on five reading comprehension benchmarks.   -->
* I am reponsible for almost all of the work and the others co-authors give me valuable suggestions about the paper writing.  


### **Conversational Image Search**
Liqiang Nie, **Fangkai Jiao**, Wenjie Wang, Yinglong Wang, and Qi Tian. _Transactions on Image Processing (TIP) 2021_.
[[pdf](https://ieeexplore.ieee.org/document/9528996)]
[[code](https://github.com/SparkJiao/LARCH)]  
* Existing works have overlooked the (1) the session structure in the conversational query, and (2) the multiform knowledge.  
* We devise a novel contextual image search scheme, LARCH, to facilitate conversational image search. 
<!-- * Besides, we construct a augmented dataset based on MMD to facilitate future research.   -->
* The main idea comes from Prof. Nie and Wenjie Wang. I have proposed several improvements to it, including: (1) increasing the edges of the constructed graph, (2) considering the session-related knowledge, and (3) introducing the gate mechanism.  
* In addition to the above suggestions, my main contributions to this work include system implemetation, experiments, the paper writing of methodology, dataset and experiments.  

### **A Self-Training Method for Machine Reading Comprehension with Soft Evidence Extraction**

Yilin Niu\*, **Fangkai Jiao**\*, Mantong Zhou, Ting Yao, Jingfang Xu and Minlie Huang. _ACL 2020._
[[pdf](https://arxiv.org/pdf/2005.05189.pdf)]
[[code](https://github.com/SparkJiao/Self-Training-MRC)]  
* The motivation of this study is that manually annotating the evidence in a paragraph for reading comprehension is expensive.    
* In this work, we propose a self-training method to supervise the evidence extractor with auto-generated evidence labels.    
<!-- * Our method achieves significant improvements on seven datasets over three MRC tasks.   -->
* My contributions in this work include the discussion of the idea, system implementation, all the experiments except those conducted on Quasar-T, and the paper writing of methodology.  

## **Preprints**

### **MERIt: Meta-Path Guided Contrastive Learning for Logical Reasoning**
**Fangkai Jiao**, Yangyang Guo, Xuemeng Song, Liqiang Nie. _Under review by ACL 2022._  
* The motivation of this work is to improve the generalization of neural logical reasoning models by devising task-oriented pre-training.  
* I am reponsible for all the work. The other co-authors help me polish the paper writing.  
* Our system achieves new state-of-art performance on both [ReClor](https://eval.ai/web/challenges/challenge-page/503/leaderboard/1347) and LogiQA.  

## **Projects**

### SLQA

*An Pytorch Implementation of Multi-Granularity Hierarchical Attention Fusion Networks (ACL 2018).* [[code](https://github.com/SparkJiao/SLQA)] (75 stars)

## **Experience**

### Damo Academy, Alibaba Group `2020.7 - 2021.2`
_Research Intern._   Advised by Dr. [Feng Ji](http://scholar.google.com/citations?user=BxWZ-ZgAAAAJ&hl=zh-CN) and Dr. [Feng-Lin Li](http://scholar.google.it/citations?user=xo_dfnMAAAAJ&hl=en)

### CoAI Group, Tsinghua University `2018.10 - 2019.8`

_Research Intern._   Advised by Prof. [Minlie Huang](http://coai.cs.tsinghua.edu.cn/hml)


## **Honors & Awards**

Dean Scholarship `School of Computer Science and Technology (2021) & School of Software (2018), Shandong University` <br>
Bronze Medal in the ACM-ICPC Asia Regional Contest `China-Final (2016) & Urumqi Site (2017), ICPC` <br>
Silver Medal in the ACM-ICPC Asia Regional Contest `Qingdao Site (2016 & 2017), ICPC` <br>
National Scholarship `Ministry of Education, 2016` <br>

<!-- Dean Scholarship `School of Software, 2018` <br> -->
<!-- Bronze Medal in the ACM-ICPC Asia Regional Contest China-Final `ICPC, 2016` <br> -->
<!-- Silver Medal in the ACM-ICPC Asia Regional Contest Qingdao Site `ICPC, 2016` <br> -->

---

<!-- ### Footer

Last updated: May 2021 -->
