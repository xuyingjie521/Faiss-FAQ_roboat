# faiss 在基于FAQ检索式智能客服上的应用


## 1、项目介绍
这是基于 FAQ 检索式智能客服自动问答项目中 在QA库中检索时用到的faiss检索的部分。
  
此小项目 demo 仅供实验参考。

## 2、运行环境
  * python3.7
  * sentence-transformers==2.1.0
  * faiss==1.7.1
  
  其中 faiss 为 cpu 版。
  
## 3、效果
10k+ 条标准question 中检索，余弦相似度为衡量标准：（其中时间单位为 s|秒）

```
「query = "我在哪儿购买会员呀？"」
the number of all vectors: 1094
total time of search top k: 7.441043853759766e-07 s
[(0.9268576, '如何购买会员'), (0.85469526, '知乎盐选会员怎么买')]
```

![运行结果图](https://github.com/xuyingjie521/Faiss-FAQ_roboat/blob/main/show_result.png)

## 交流
  本项目作为笔者在之前工作中项目背景下的一小部分实验 demo。 
  源码和数据已经在项目中给出。
  
  如需要更深一步的交流，请发送消息至邮箱 1812316597@qq.com，或者在 Github 上直接留言。