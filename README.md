# MPC and DP
A small repository to contain all the resources of Multi-Party Computation and Differential Privacy used by me to develop background for IBM Research collab project. \
[Update] Note: This will not contain any of the research work in general; just all the literature-reading.

----------------------------------------------------------------------------------------------------------------------------------


### 11<sup>th</sup> April - 17<sup>th</sup> April, 2021

* Secure Multiparty Computation (MPC) by Yehuda Lindell (cryptographic protocols / survey): [Paper](https://eprint.iacr.org/2020/300.pdf) |
                                                                                            [Video](https://youtu.be/Li2QJ8yImoY)

* MP-SPDZ: A Versatile Framework for Multi-Party Computation by Marcel Keller : [Paper](https://eprint.iacr.org/2020/521.pdf)

* SCALE-MAMBA Documentation & Guide : [link](https://homes.esat.kuleuven.be/~nsmart/SCALE/)
                                                                                            
* Morten Dahl's blogs on MPC and SPDZ Protocol : [link](https://mortendahl.github.io/2017/09/10/the-spdz-protocol-part2/)

* Bristol Cryptography Blog : [link](https://bristolcrypto.blogspot.com/2016/10/what-is-spdz-part-1-mpc-circuit.html)

* A Pragmatic Introduction to Secure Multi-Party Computation: [PDF](https://securecomputation.org/docs/pragmaticmpc.pdf)


### 18<sup>th</sup> April - 24<sup>th</sup> April, 2021

* IBM's Differential Privacy library `diffprivlib` : [installation guide](https://github.com/IBM/differential-privacy-library) | 
                                                     [example notebooks](https://github.com/IBM/differential-privacy-library/tree/main/notebooks) | 
                                                     [detailed documentation](https://diffprivlib.readthedocs.io/en/latest/)
                                                     
* Google's Differential Privacy library `Privacy on Beam` : [documentation](https://opensource.googleblog.com/2020/06/expanding-our-differential-privacy.html) | 
                                                     [codelab](https://codelabs.developers.google.com/codelabs/privacy-on-beam/#0) |
                                                     [Github](https://github.com/google/differential-privacy)

* OpenMined's Python wrapper for Privacy on Beam `PyDP` : [Github](https://github.com/OpenMined/PyDP) | 
                                                          [Slack](https://openmined.slack.com/join/shared_invite/zt-p8y1423n-SYC4uwI2yUHj4gSlHbslAw#/) |
                                                          [excellent examples](https://github.com/OpenMined/PyDP/tree/dev/examples) | 
                                                          [resources & tutorials](https://github.com/OpenMined/PyDP/blob/dev/resources.md)
                                                          
* Facebook's high-speed library for training PyTorch models with differential privacy `Opacus` : [Tutorial](https://opacus.ai/tutorials/)


### 2<sup>nd</sup> May - 8<sup>th</sup> May, 2021

* k-anonymity : [Wikipedia](https://en.wikipedia.org/wiki/K-anonymity)

* OpenDP's `SmartNoise SDK` : [GitHub](https://github.com/opendp/smartnoise-sdk)

* Google's Differential Privacy library Algo's documentation (C++) : [Docu](https://github.com/google/differential-privacy/tree/main/cc/docs)

* TED's non-technical writing on Differential Privacy : [Link](https://desfontain.es/privacy/differential-privacy-awesomeness.html)


### 9<sup>th</sup> May - 15<sup>th</sup> May, 2021

*  Frankmcsherry's Blog  : [Link](https://github.com/frankmcsherry/blog/blob/master/posts/2016-02-06.md)


### 16<sup>th</sup> May - 22<sup>nd</sup> May, 2021

*  Uber's Differential Privacy Framework (based on **Elastic Sensitivity**) `CHORUS`: [First Blog](https://medium.com/uber-security-privacy/differential-privacy-open-source-7892c82c42b6) | 
                                                          [Updated Blog](https://medium.com/uber-security-privacy/uber-open-source-differential-privacy-57f31e85c57a) |
                                                          [Video presentation](https://www.usenix.org/conference/enigma2018/presentation/ensigns) | 
                                                          [Elastic Sensitivity paper](https://arxiv.org/pdf/1706.09479.pdf) | 
                                                          [GitHub](https://github.com/uber-archive/sql-differential-privacy)
                                                          
                                                          
### 30<sup>th</sup> May - 5<sup>th</sup> June, 2021

*  Hierarchial Time Series: [Tutorials](https://medium.com/opex-analytics/hierarchical-time-series-101-734a3da15426)

*  Vector autoregression : [Wikipedia](https://en.wikipedia.org/wiki/Vector_autoregression) | 
                           [Tutorials](https://otexts.com/fpp2/VAR.html) | 
                           [PennState Docu](https://online.stat.psu.edu/stat510/lesson/11/11.2)

* ARIMA model (Autoregressive Integrated moving averages : [Wikipedia](https://en.wikipedia.org/wiki/Autoregressive_integrated_moving_average) | 
                                                           [Tutorials](https://otexts.com/fpp2/non-seasonal-arima.html)
                                                           

* Working mechanisms of different DP libaries : [Privacy on Beam](https://github.com/google/differential-privacy/blob/main/cc/docs/algorithms/bounded-sum.md) | 
                                                [OpenDP](https://github.com/opendp/smartnoise-samples/blob/master/analysis/basic_data_analysis.ipynb)


### 6<sup>th</sup> June - 12<sup>th</sup> June, 2021

*  Distributed DP mechanisms into MPC protocols: [Paper 1](https://www.usenix.org/system/files/sec20-bohler.pdf) | 
                                                 [Paper 2](http://elaineshi.com/docs/ndss2011.pdf) | 
                                                 [Paper 3](https://www.researchgate.net/profile/Vibhor-Rastogi/publication/221213330_Differentially_private_aggregation_of_distributed_time-series_with_transformation_and_encryption/links/54f562f50cf2ba615065cdb1/Differentially-private-aggregation-of-distributed-time-series-with-transformation-and-encryption.pdf)
                                                 
*  Laplace mechanism for adding noise in ε-differential privacy: [Paper 1](https://privacytools.seas.harvard.edu/files/privacytools/files/the_algorithmic_foundations_of_differential_privacy_0.pdf) | 
                                                 [Slides from Roger Grosse](https://www.cs.toronto.edu/~rgrosse/courses/csc2515_2019/slides/lec11-slides.pdf) | 
                                                 [Lecture of Gautam Kamath](https://www.youtube.com/watch?v=IGQe9BN1TZs) | 
                                                 [Truncated Laplacian mechanism used by IBM](https://arxiv.org/pdf/1810.00877v1.pdf)

*  Geometric mechanism used in IBM diffprivlib: [Paper](https://arxiv.org/pdf/0811.2841.pdf)
