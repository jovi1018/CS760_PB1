# CS760_PB1
**Animal Individual Detection and Identification using Deep Learning:**

1) identify monkey individuals using Metric Learnig 

    i) *Constrastive Loss* and *Triplet Loss*, *VGG16 Classification model* as baseline

    ii) *Closed set* and *Open set*

    iii) Dataset: https://drive.google.com/drive/folders/1LU9J415CWppI-LRM9Thw-0dG2F8rBOkb?usp=sharing


**Code Documentation:**

1) Contrastive loss implementation is inspired by Adrian Rosebrock: https://www.pyimagesearch.com/2021/01/18/contrastive-loss-for-siamese-networks-with-keras-and-tensorflow/

2) Triplet loss implementation is using the existing transorflow addons losses: https://www.tensorflow.org/addons/tutorials/losses_triplet


**Hyperparameters tuning during cross validation step:**

1) *Learning rate*: search space [1e-5, 1e-4, 1e-3, 1e-2, 1e-1]
2) *value k of kNN*: search space [5, 11, 21,  31]
3) openset - *distance threshold (d_t)*: search space [0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1]
