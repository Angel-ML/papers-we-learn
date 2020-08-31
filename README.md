# papers-we-learn
旨在归纳Angel高性能分布式机器学习与图计算平台实践过程中所借鉴的计算机领域论文，理论与实践相结合
## distributed systems
收录angel实现分布式参数服务器、以及机器学习、图计算框架时借鉴的论文
1. Resilient Distributed Datasets A Fault-Tolerant Abstraction for In-Memory Cluster Computing(Spark).pdf  [paper](https://www.usenix.org/system/files/conference/nsdi12/nsdi12-final138.pdf)
2. Parameter Server for Distributed Machine Learning(Parameter Server).pdf [paper](https://pdfs.semanticscholar.org/30e9/4e24d67994c5a8e2f20f852a51d28a720de2.pdf)
3. Angel a new large-scale machine learning system(Angel).pdf [paper](https://watermark.silverchair.com/nwx018.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAApgwggKUBgkqhkiG9w0BBwagggKFMIICgQIBADCCAnoGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQM7WLJn4lqzHtLysYMAgEQgIICS1NYL7L5PcMcKzXEss8zpE5bJGQM8Lp_eK177hnLQYZj8Po6_25C0NaYCld_YGmKREgMhLy498bUT5vRKrUncFOkkVFmfLIwxZ-vUg0Czgo63lZWZYgjHBe8jt0zDKVlvWt4lIgP0DDqJvmXjzqRXS3uw8CPHPevqXpFpBwqw5UU-Txky0YxP_VWRuF3qpXMSqqk8nfiTCracFXuwNO2VSOibKcjGUTA-iiI2jzwd2VbKZij1pl9FLBdvtf-cay203nXfHdMbks2h9aETkKGNinch2B46oBifczW8aw4-OVsKTS2SSgt0FqLFDPr-_lzEEYKSXhkSFkQPSpRemrAuTQr9cOPWjk5WK9tMP862Ld19d7hDy6Q7_mawu0SKkjiS6pfXQ6EpJlck97BwibHUYdlDGsSWwi7mMcsPIxxiGNFU7SoDuHTXDyiOSskg6HezlGwyZ5ZC_BMWrzW3auluw5SrL_o87NRhkSSnDJ5W5jszzvjjTbGLDGWjsusHieXOzVkJUiSmUF3kkr8wz_DV2fpjffdRgsxBkeSMPEhpnmYIaP-uB9CRnbhqFTy7FzscG0GgrgvhGI8CEd255b0HyYLLrdhUYQ-2zZnP0QokWtoVadt8L1VLRQFqut76VlaId8s8mDwqnONMYaDdXjxyRcg1nIW7hH3eAI_eYfEDF2xipmuMrv8uo4eY_aiiAhJYGg7O9oesspWGS9dVkP0TuujwnRweNo3CKyGarux1re9ysLu105TNUFM3NfCDCal5My2m6cPfvUnYrEZ)
4. Pregel A System for Large-scale Graph Processing(Pregel).pdf [paper](https://kowshik.github.io/JPregel/pregel_paper.pdf)
5. Distributed GraphLab A Framework for Machine Learning and Data Mining in the cloud(GraphLab).pdf [paper](http://vldb.org/pvldb/vol5/p716_yuchenglow_vldb2012.pdf)
6. PowerGraph Distributed Graph-Parallel Computation on Natural Graphs(PowerGraph).pdf [paper](https://www.usenix.org/system/files/conference/osdi12/osdi12-final-167.pdf)
7. Graphx Unifying Data-Parallel and Graph-Parallel Analytics(Graphx).pdf [paper](https://endymecy.gitbooks.io/spark-graphx-source-analysis/content/docs/graphx.pdf)
8. PSGraph How Tencent trains extremely large-scale graphs with Spark(PSGraph).pdf [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9101887)

## graph mining
收录angel实现的传统图算法
1. The PageRank Citation Ranking Bringing Order to the Web(Pagerank).pdf [paper](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=6B71249025955741845EB201BE407DD2?doi=10.1.1.38.5427&rep=rep1&type=pdf)
2. The H-index of a network node and its relation to degree and coreness(kcore hindex).pdf [paper](https://scinapse.io/papers/2261717057)
3. HyperAnf Approximating the Neighbourhood Function of Very Large Graphs on a Budget(HyperAnf).pdf [paper](https://arxiv.org/pdf/1011.5599.pdf)
4. Centralities in Large Networks Algorithms and Observations(Closeness).pdf [paper](https://www.cs.cmu.edu/~ukang/papers/CentralitySDM2011.pdf)

## graph embedding 
收录angel实现的图表示学习相关论文
1. DeepWalk Online Learning of Social Representations(DeepWalk).pdf [paper](https://arxiv.org/pdf/1403.6652.pdf)
2. LINE Large-scale Information Network Embedding(LINE).pdf [paper](https://arxiv.org/pdf/1503.03578.pdf)
3. Metapath2Vec Scalable Representation Learning for Heterogeneous Networks(Metapath2Vec).pdf [paper](https://ericdongyx.github.io/papers/KDD17-dong-chawla-swami-metapath2vec.pdf)

## graph neural network
收录angel已实现或即将实现的图神经网络相关论文
1. Graph Convolutional Neural Networks for Web-Scale Recommender Systems(Pinsage).pdf [paper](https://arxiv.org/pdf/1806.01973.pdf)
2. How Powerful Are Graph Neural Networks(GNN and WL Test).pdf [paper](https://arxiv.org/pdf/1810.00826.pdf)
3. Inductive Representation Learning On Large Graphs(Graphsage).pdf [paper](https://arxiv.org/pdf/1706.02216.pdf)
4. Semi-Supervised Classification With Graph Convolutional Networks(GCN).pdf [paper](https://arxiv.org/pdf/1609.02907.pdf)
5. DeepTrax Embedding Graphs of Financial Transactions(Financial).pdf [paper](https://arxiv.org/pdf/1907.07225.pdf)


## machine learning
收录angel已实现或即将实现的机器学习算法论文
1. Ad Click Prediction ~ a View from the Trenches(FTRL).pdf [paper](https://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/41159.pdf)
2. An Introduction to Logistic Regression Analysis and Reporting.pdf [paper](https://datajobs.com/data-science-repo/Logistic-Regression-[Peng-et-al].pdf)
3. Attentional Factorization Machines ~ Learning the Weighted of Feature Interactions via Attention Networks(AttentionFM).pdf [paper](https://www.ijcai.org/Proceedings/2017/0435.pdf)
4. Factorization Machines(FM).pdf [paper](https://www.csie.ntu.edu.tw/~b97053/paper/Rendle2010FM.pdf)
5. DeepFM A Factorization-Machine based Neural Network for CTR Prediction(DeepFM).pdf [paper](https://www.ijcai.org/Proceedings/2017/0239.pdf)
6. xDeepFM~ Combining Explicit and Implicit Feature Interactions for Recommender Systems(xDeepFM).pdf [paper](https://arxiv.org/pdf/1803.05170.pdf)
7. LDA ~ A Robust and Large-scale Topic Modeling System(LDA).pdf [paper](http://www.vldb.org/pvldb/vol10/p1406-yu.pdf)
8. Product-based Neural Networks for User Response Prediction(PNN).pdf [paper](https://arxiv.org/pdf/1611.00144.pdf)
9. Space-Efficient Online Computation of Quantile Summaries(Quantile Summaries).pdf [paper](http://infolab.stanford.edu/~datar/courses/cs361a/papers/quantiles.pdf)
10. Web-Scale K-Means Clustering(Kmeans).pdf [paper](https://www.eecs.tufts.edu/~dsculley/papers/fastkmeans.pdf)
11. Wide & Deep Learning for Recommender Systems(DeepAndWide).pdf [paper](https://arxiv.org/pdf/1606.07792.pdf)
12. XGBoost ~ A Scalable Tree Boosting System(XGBoost).pdf [paper](https://arxiv.org/pdf/1603.02754.pdf)
13. Deep & Cross Network for Ad Click Predictions(DCN).pdf [paper](https://arxiv.org/pdf/1708.05123.pdf)

## nlp

自然语言处理相关的算法论文

1. Distributed Representations of Words and Phrases and their Compositionality (Word2Vec).pdf [paper](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
