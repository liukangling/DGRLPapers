# DGRLPapers
Papers on Dynamic Graph Representation Learning.



## papers


### dynamic graphs --> snaphots of graphs at different time steps
1.Goyal P, Kamra N, He X, et al. DynGEM: Deep Embedding Method for Dynamic Graphs. 2018. [paper](http://cn.arxiv.org/pdf/1805.11273)
DynGEM将动态图分成了K个graph snapshot, 第l+1层的参数由第l层的参数初始化,通过增加编码器的layer的宽度和深度来自动构建neural network,相邻的layer需满足自定义的PropSize条件,这样最终生成的embedding具有一定的稳定性(stable constant).



Li Y, Yu R, Shahabi C, et al. Diffusion Convolutional Recurrent Neural Network: Data-Driven Traffic Forecasting. 2017. [paper](http://cn.arxiv.org/pdf/1707.01926) [code](https://github.com/liyaguang/DCRNN)
