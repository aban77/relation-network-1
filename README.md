# relation-network
keras implementation of  [A simple neural network module for relational reasoning](https://arxiv.org/pdf/1706.01427.pdf)


Relation network is a noval neural network introduced by deepmind in [A simple neural network module for relational reasoning](https://arxiv.org/pdf/1706.01427.pdf). It can achieve super-human performance in challenging visual question answering datasets such as CLEVR.

I implement Relation network using keras and train it on a challenging visual question answering dataset called [Cornell NLVR](https://github.com/cornell-lic/nlvr). The training is in progress. The temporal test accuracy is 89.10%, which is much higher than the previous state of the art (61.99%).

Santoro, A., Raposo, D., Barrett, D. G., Malinowski, M., Pascanu, R., Battaglia, P., & Lillicrap, T. (2017). A simple neural network module for relational reasoning. In Advances in neural information processing systems (pp. 4967-4976).
