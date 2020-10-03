# SCGNet-Sparsely connected CNN for Efficient Automatic Modulation Recognition
Abstract- This paper proposes a convolutional neural network (CNN) called SCGNet for low-complexity and robust modulation recognition in intelligent communication receivers. Principally, the network combines two types of sparse convolutional layers—depthwise and grouped in an architecture—to achieve a few trainable parameters while maintaining high recognition accuracy. The network architecture leverages sparsely connected convolutional layers in three principal modules: speed–accuracy tradeoff (SAT), deep feature extraction and processing (DFEP), and generic feature extraction (GFE) data pre-processing module. SAT deploys depthwise convolutional layers to extract features generated by GFE, achieving a good tradeoff between complexity and accuracy. In addition to SAT, DFEP employs a cascade of regular grouped convolutional layers for mining more discriminative features from SAT via a multilayer transformation module. The aim of the cascade is to prevent a loss of essential details of the signal as the network becomes deeper. Additionally, skip connections are deployed between sub-blocks within SAT and DFEP to allow inter-module feature sharing, for handling inter-block features loss. Experimental results indicate that SCGNet achieves an overall recognition accuracy of around 94.39 % at a signal-to-noise ratio of +20 dB on the RadioML2018.01A dataset.
