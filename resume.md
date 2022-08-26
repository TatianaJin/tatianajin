# Tatiana Jin

> Last updated: Aug 26, 2022

```text
The Chinese University of Hong Kong
Husky Data Lab                          Email: tjin at cse.cuhk.edu.hk
Department of Computer Science          Github: https://github.com/tatianajin
```

## Education

``` 2019-Present ``` PhD Candidate, Computer Science, The Chinese University of Hong Kong.

``` 2019 ``` Master of Philosophy, Computer Science, The Chinese University of Hong Kong.

``` 2017 ``` Master of Science, Computer Science, The Chinese University of Hong Kong.

``` 2015 ``` Bachelor of BA, The Chinese University of Hong Kong.

## Research

### Selected Academic Projects

``` 2021-2022 ``` Circinus: Fast Redundancy-Reduced Subgraph Matching with Scalability

* This project focuses on supporting high-performance subgraph matching on complex queries with low computational redundancy and low memory usage.
* Acted as project leader. Designed and jointly implemented the query optimization and execution pipeline, which allows low computation redundancy and low memory usage for query processing, and has been proven by experimental evaluation to provide up to several orders of magnitude speedup on various data and query settings.
* Co-designed a cost-based partial match compression mechanism, which can be applied generally to state-of-the-art subgraph matching algorithms and has been experimentally proven to achieve an average of 96.45% redundancy reduction for labeled queries and 87.30% for unlabeled queries.

``` 2018-Present ``` Ursa: Improving Resource Utilization by Timely Fine-Grained Scheduling

* This project aims at improving cluster resource utilization by fine-grained, timely resource sharing among multiple jobs in a quota group. Ursa integrates both  scheduling and execution frameworks to provide runtime resource demand capturing and timely resource privision and reallocation.
* Acted as project leader. Designed and jointly implemented the scheduling framework, which is experimentally evaluated to achieve over 30% resource utilization improvement over existing solutions that are generally adopted in industry.
* Ursa also supports high-level APIs such as Spark-like dataset API, Pregel API, and SQL. Ursa implements a distributed analytical SQL engine by using Hive and adopts a column-oriented design for high-performance OLAP.

### Selected Industry Projects

``` 2019-2022 ``` ``` Huawei ``` Seastar: Vertex-Centric Programming for Graph Neural Networks

* Seastar is a novel Graph Neural Network (GNN) training framework, which offers a vertex-centric programming model so that users can focus on the logic of a single vertex and program GNNs with idiomatic Python syntax. Seastar identifies abundant operator fusion opportunities in the computational graphs of GNN training. With novel designs such feature-adaptive groups, locality-centric execution and dynamic load balancing, Seastar generates high-performance fused kernels for forward and backward passes. Seastar achieves significant performance improvements over popular systems such as DGL and PyG.

``` 2019-2021 ``` ``` Alibaba ``` ParSync: Scaling Large Production Clusters with Partitioned Synchronization

* Partitioned synchronization is a novel state sharing design for distributed scheduling. It has been deployed and is running stably in the production cluster in Alibaba. It can schedule billions of tasks each day on 100 thousand machines, while it also achieves low-latency and high-quality scheduling. The results of part of the core research in this project has been published in USENIX ATC 2021 and the paper was awarded the Best Paper.

### Publications

Guanxian Jiang, Qihui Zhou, **Tatiana Jin**, Boyang Li, Yunjian Zhao, Yichao Li, and James Cheng.
VSGM: View-Based GPU-Accelerated Subgraph Matching on Large Graphs.
SC 2022. ```Best Student Paper Finalist```

Yuntao Gui, Yidi Wu, Han Yang, **Tatiana Jin**, Boyang Li, Qihui Zhou, James Cheng, and Fan Yu.
HGL: Accelerating Heterogeneous GNN Training with Holistic Representation and Optimization.
SC 2022.

**Tatiana Jin**, Boyang Li, Yichao Li, Qihui Zhou, Qianli Ma, Yunjian Zhao, Hongzhi Chen, and James Cheng.
Circinus: Fast Redundancy-Reduced Subgraph Matching.
SIGMOD Conference 2023.

Yidi Wu, Kaihao Ma, Zhenkun Cai, **Tatiana Jin**, Boyang Li, Chengguang Zheng, James Cheng, Fan Yu.
Seastar: vertex-centric programming for graph neural networks.
EuroSys 2021: 359-375.

Yidi Wu, Yuntao Gui, **Tatiana Jin**, James Cheng, Xiao Yan, Peiqi Yin, Yufei Cai, Bo Tang, Fan Yu.
Vertex-Centric Visual Programming for Graph Neural Networks.
SIGMOD Conference 2021: 2803-2807.

Yihui Feng, Zhi Liu, Yunjian Zhao, **Tatiana Jin**, Yidi Wu, Yang Zhang, James Cheng, Chao Li, Tao Guan.
Scaling Large Production Clusters with Partitioned Synchronization.
USENIX Annual Technical Conference 2021: 81-97. ``` Best Paper Award ```

Kaili Ma, Haochen Yang, Han Yang, **Tatiana Jin**, Pengfei Chen, Yongqiang Chen, Barakeel Fanseu Kamhoua, James Cheng.
Improving Graph Representation Learning by Contrastive Regularization.
CoRR abs/2101.11525 (2021).

**Tatiana Jin**, Zhenkun Cai, Boyang Li, Chengguang Zheng, Guanxian Jiang, James Cheng.
Improving resource utilization by timely fine-grained scheduling.
EuroSys 2020: 20:1-20:16.

Yuzhen Huang, Xiao Yan, Guanxian Jiang, **Tatiana Jin**, James Cheng, An Xu, Zhanhao Liu, Shuo Tu.
Tangram: Bridging Immutable and Mutable Abstractions for Distributed Data Analytics.
USENIX Annual Technical Conference 2019: 191-206.

Yuzhen Huang, **Tatiana Jin**, Yidi Wu, Zhenkun Cai, Xiao Yan, Fan Yang, Jinfeng Li, Yuying Guo, James Cheng.
FlexPS: Flexible Parallelism Control in Parameter Server Architecture.
Proc. VLDB Endow. 11(5): 566-579 (2018).

## Skills

### Systems Research

* Graph databases: very familiar with Neo4J, RedisGraph, and AgensGraph.
* RDBMS: familiar with Hive, Apache Calcite, Apache Kylin, and Clickhouse.
* Batch processing: very familiar with Hadoop and Spark.
* Machine learning: very familiar with Parameter Server.

### Programming

* Systems/Databases: ```SQL``` ```Cypher``` ```PyTorch``` ```TensorFlow``` ```DGL``` ```PyG``` ```Hadoop``` ```Spark```
* Programming Languages: ```C/C++``` ```Python``` ```Java``` ```Rust```  ```Bash```
* Project management tools: ```Git``` ```CMake```
* Web development: ```HTML``` ```CSS``` ```JavaScript``` ```NodeJS``` ```Laravel``` ```JQuery``` ```Elementor```

### Languages

```Chinese-Mandarin``` ```Chinese-Cantonese``` ```English``` ```Japanese``` ```Spanish```

## External Reviewer

* ```2022``` VLDB
* ```2019``` VLDB, SIGMOD
* ```2018``` VLDB
* ```2017``` ICDE, VLDB
