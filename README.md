# DPDFD
It is a code snippet of our IJCAI 2023 paper [Model Conversion via Differentially Private Data-Free Distillation](https://arxiv.org/abs/2304.12528). This is the main code for achieving differential privacy. It can be applied directly to any distillation process to train privacy-preserving student models.

Running this code needs a pre-trained teacher and images (private data or synthetic data generated by a generator). Other parameters are hyperparameters. You will get a differentially private output `s_out_new` after running it. You can think of it as a differentially private label predicted by teacher(s) to update the student. 

The calculation of privacy budget can be found in our paper.
