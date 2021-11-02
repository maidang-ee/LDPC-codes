# Self-corrected LDPC codes decoding in Neural Network 

Based on the source code provided by paper A Model-Driven Deep Learning Method for Normalized Min-Sum LDPC Decoding

  With the applications of deep learning networks booming in physical layer communication, deep-learning-based
channel decoding methods have become a research hotspot. However, the high complexity hinders the application of deep neural network (DNN) on long code. 
  A model-driven deep learning method for normalized min-sum (NMS) low-density parity-check (LDPC) decoding was proposed along with another higher improvment method Shared Neural Normalized Min Sum (SNNMS). 
  By unfolding the iterative decoding progress between checking nodes (CNs) and variable nodes (VNs) into a feedforward propagation network, we can make use of the advantages of both model-driven deep learning methods and conventional normalized min-sum (CNMS) LDPC decoding method. The shared neural normalized min-sum (SNNMS) decoding network seems to reduce the number of correction factors. However, this method only learn one parameter which is normalization factor. 
  Our proposed method will first reduce the number of variable nodde (VN) neurons by erasing potential incorrect bit nodes. Then, we will combine both normalized min-sum and offset min-sum algorithms in check node (CN) updating process and apply deep neural network (DNN) to train both normalized factors as weights and offset factors as biases. 

This repository contains the code for Shared Neural Normalized Min-Sum (SNNMS) and Neural Sefl-corrected Min-Sum (NSCMS).
main.py: you can choose two kinds of neural decoder: SNNMS and NSCMS.
Generation_matrix.py: load LDPC_576_432.alist and LDPC_576_432.gamt to generate check matrix H and generator matrix G.
