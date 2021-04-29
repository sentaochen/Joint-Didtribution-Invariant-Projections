# Joint Distribution Invariant Projections (JDIP)


A demo application running on the Office-Caltech data set with the 4096-dimensional VGG-FC6 features.
Domain Adaptation by Joint Distribution Invariant Projections, IEEE Transactions on Image Processing, 2020 [[pdf](https://ieeexplore.ieee.org/document/9159880)]  
Authors: Sentao Chen, Mehrtash Harandi, Xiaona Jin, and Xiaowei Yang.  

An illustration of the proposed JDIP approach for domain adaptation, which exploits a couple of projections to match the source and target joint distributions under the L^{2}-distance.   
![procedure](procedure.jpg)

The codes are written based on the ManOpt provided by Z. Wen and W. Yin. A feasible method for optimization with orthogonality constraints. Mathematical Programming 2013  
The data are provied by Xian Y, Lampert C H, Schiele B, et al. Zero-shot learning -- A comprehensive evaluation of the good, the bad and the ugly. IEEE TPAMI 2018  

Please consider citing our work if you find it helpful to your research:  
@article{Chen2020Domain,
  author={Chen, Sentao and Harandi, Mehrtash and Jin, Xiaona and Yang, Xiaowei},
  journal={IEEE Transactions on Image Processing}, 
  title={Domain Adaptation by Joint Distribution Invariant Projections}, 
  year={2020},
  volume={29},
  number={},
  pages={8264-8277},
  doi={10.1109/TIP.2020.3013167}}
