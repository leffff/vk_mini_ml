My Solution to [VK Mini ML](https://cups.online/ru/contests/vk-miniml) <br>
Target metric - [recall@10](https://medium.com/@m_n_malaeb/recall-and-precision-at-k-for-recommender-systems-618483226c54) <br>
* [Node2Vec + KDTree baseline](node2vec_baseline.ipynb) (only adjacency)
  * Public: 0.0028328611898017
* [ALS](als.ipynb) (adjacency matrix with h weigths)
  * Public: 0.09346474661630469
* [ALS](undirectd_als.ipynb) (undirected adjacency matrix with h weigths)
  * Public: 0.17478968151772684
