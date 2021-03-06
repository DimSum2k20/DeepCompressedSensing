# Project Compressed Sensing - 3rd Year ENSAE

The main results for our experiments can be found in the notebook `GenerativeCS.ipynb`. Analysis of the results can be found in the report. We implemented the algorithms from [Modeling Sparse Deviations for Compressed Sensing using Generative Models](https://arxiv.org/abs/1807.01442), [Compressed Sensing using Generative Models](https://arxiv.org/abs/1703.03208) and [Deep Compressed Sensing](https://arxiv.org/abs/1905.06723) in PyTorch.

To reduce the size of the notebook and for better readibility we split the core codes in different folders. It is organised as follow:
- `utils.py` contain helper functions to handle the datasets and the plots
- `lasso.py` contains lasso and Basis Pursuit codes for recovery
- `vae.py` contains the codes for various VAE architectures
- `gan.py` contains the GAN codes and `logger.py` contains helper functions to store GAN results
- `cs.py` contains the codes for [Modeling Sparse Deviations for Compressed Sensing using Generative Models](https://arxiv.org/abs/1807.01442) and [Compressed Sensing using Generative Models](https://arxiv.org/abs/1703.03208)
- `dcs.py` contains the codes for [Deep Compressed Sensing](https://arxiv.org/abs/1905.06723)

Papers/ref:
- [Deep Compressed Sensing](https://arxiv.org/abs/1905.06723) ([repo](https://github.com/deepmind/deepmind-research/tree/master/cs_gan)) [2019]
- [Modeling Sparse Deviations for Compressed Sensing using Generative Models](https://arxiv.org/abs/1807.01442) ([repo](https://github.com/ermongroup/sparse_gen)) [2018]
- [Compressed Sensing using Generative Models](https://arxiv.org/abs/1703.03208) ([repo](https://github.com/AshishBora/csgm)) [2017]
- [Compressed Sensing Donoho](http://www.ece.ubc.ca/~janm/Papers_RG/Donoho_IT_April06.pdf)
- [Tutorial on Variational Autoencoders](https://arxiv.org/pdf/1606.05908.pdf) 
- [DCGANs](https://arxiv.org/pdf/1511.06434.pdf)
- [LASSO](https://cs.nyu.edu/~roweis/csc2515-2006/readings/lasso.pdf)
