# Wukong for Linked Data

Wukong, a graph-based distributed in-memory store that leverages efficient graph exploration to provide highly concurrent and low-latency queries over big linked data.


## Feature Highlights

* High-performance and scalable in-memory store
* Fast and concurrent query processing by graph exloration
* Efficient and accurate SPARQL planner
* Enabling RDMA feature of InfiniBand networking

For more details see [Wukong Project](http://ipads.se.sjtu.edu.cn/projects/wukong), including new features, roadmap, instructions, etc.


## Getting Started

* [Installation](docs/INSTALL.md)
* [Tutorials](docs/TUTORIALS.md)


## License

Wukong is released under the [Apache 2.0 license](http://www.apache.org/licenses/LICENSE-2.0.html).

If you use Wukong in your research, please cite our paper:
   
    @inproceedings{osdi2016wukong,
     author = {Shi, Jiaxin and Yao, Youyang and Chen, Rong and Chen, Haibo and Li, Feifei},
     title = {Fast and Concurrent RDF Queries with RDMA-based Distributed Graph Exploration},
     booktitle = {12th USENIX Symposium on Operating Systems Design and Implementation},
     series = {OSDI '16},
     year = {2016},
     month = Nov,
     isbn = {978-1-931971-33-1},
     address = {GA},
     pages = {317--332},
     url = {https://www.usenix.org/conference/osdi16/technical-sessions/presentation/shi},
     publisher = {USENIX Association},
    }


## Academic and Reference Papers

[**SOSP**] [Sub-millisecond Stateful Stream Querying over Fast-evolving Linked Data](docs/wukong+s-sosp17.pdf). Yunhao Zhang, Rong Chen, and Haibo Chen. Proceedings of the 26th ACM Symposium on Operating Systems Principles, Shanghai, China, October, 2017. 

[**OSDI**] [Fast and Concurrent RDF Queries with RDMA-based Distributed Graph Exploration](docs/wukong-osdi16.pdf). Jiaxin Shi, Youyang Yao, Rong Chen, Haibo Chen, and Feifei Li. Proceedings of 12th USENIX Symposium on Operating Systems Design and Implementation, Savannah, GA, US, Nov, 2016. 




