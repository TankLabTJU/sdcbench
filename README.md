# SDCBench
SDCBench is a benchmark suite and evaluation methodology for latency entropy measurement in datacenters. SDCBench seeks to help cloud tenants and providers understand the application isolation ability in datacenter by colocating workloads and observing their performance variation in cloud systems. 
SDCBench includes 16 representative applications selected from today's well-known benchmarks that across a wide range of cloud scenarios. It first proposes the concept of latency entropy and implements a robust methodology to measure the performance isolation ability in datacenters. 
---

## 项目结构
<details>
<summary>展开查看</summary>
<pre><code>
SDCBench
|
├─── socialnetwork-func
|       ├── yaml-func
|       ├── yaml-db
├─── mongodb
|       ├── yaml
├─── solr
|       ├── yaml
├─── dnninference
|       ├── dssm-minclass
|       ├── half
|       ├── mobilenet
|       ├── resnet
|       ├── ssd
|       ├── textcnn
|       ├── yamnet
├─── tailbench
|       ├── img-dnn
|       ├── masstree
|       ├── xapian
├─── tpc-w
├─── cloudsuite
|       ├── memcached
├─── functionbench
|       ├── ALU
|       ├── DiskIO
|       ├── Matmul
├─── TensorflowBench
|       ├── alexnet
|       ├── googlenet
|       ├── inception3
|       ├── inception4
|       ├── vgg11
|       ├── vgg16
├─── Spark
|       ├── DecisionTree
|       ├── LinearRegression
|       ├── PCA
|       ├── Terasort
|       ├── PageRank
|       ├── PregelOperation
|       ├── LabelPropagation
|       ├── Kmeans
├─── Parsec
|       ├── blackscholes
|       ├── canneal
|       ├── fluidanimate
|       ├── freqmine
|       ├── streamcluster
├─── Bigdatabench
|       ├── Union
|       ├── OrderBy
|       ├── CF
|       ├── MD5
|       ├── CC
├────────────────────────

</code></pre>
</details>
