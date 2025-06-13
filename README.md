# E-STGCN: Extreme Spatiotemporal Graph Convolutional Networks for Air Quality Forecasting

In this study, we propose an Extreme Spatiotemporal Graph Convolutional Networks (E-STGCN) framework by integrating the extreme value theory with graph convolution networks and long-short term memory netwokrs for spatiotemporal forecasting of air pollutant conecentrations. Our study focuses on publicly available air quality dataset in different locations of Delhi, India[1].

![Air quality monitoring stations](https://github.com/mad-stat/E_STGCN/blob/main/Images/Corr_Plot_Revised.png)

Usage of the repository for the paper "Extreme Spatiotemporal Graph Convolutional Networks for Air Quality Forecasting [2]".

* We propose the E-STGCN framework, which integrates graph convolutional networks for spatial modeling, LSTM networks to capture long-range temporal dependencies, and an EVT-based training mechanism designed to enhance forecasting accuracy, particularly in the presence of extreme air pollution events.

![Model_Image](https://github.com/mad-stat/E_STGCN/blob/main/Images/E_STGCN_Model_Image.png) 

* In this repository, we present the application of the proposed E-STGCN model with Delhi's air quality datasets from 37 monitoring stations [1].  
  
* The [ESTGCN Code](https://github.com/mad-stat/E_STGCN/blob/main/Codes/E_STGCN_Code_Share.ipynb), [GPD fitting](https://github.com/mad-stat/E_STGCN/blob/main/Codes/POT_Fitting_Code_Share.R) file contains the source code and the implementation of the proposed E-STGCN model. 

* Results obtained in the paper for the air quality datasets can be computed using the implementation files in this repository for the sake of replicability and reproducibility of our paper. 


## Citing Our Work
Panja, M., Chakraborty, T., Biswas, A., & Deb, S. (2024).\
E-STGCN: Extreme Spatiotemporal Graph Convolutional Networks for Air Quality Forecasting.\
arXiv preprint arXiv:2411.12258.

@article{panja2024stgcn,\
  title={E-STGCN: Extreme Spatiotemporal Graph Convolutional Networks for Air Quality Forecasting},\
  author={Panja, Madhurima and Chakraborty, Tanujit and Biswas, Anubhab and Deb, Soudeep},\
  journal={arXiv preprint arXiv:2411.12258},\
  year={2024}
}


## References
* <a id="1">[1]</a> [Delhi air quality data](https://cpcb.nic.in/real-time-air-qulity-data/)
* <a id="2">[2]</a> [Extreme Spatiotemporal Graph Convolutional Networks for Air Quality Forecasting.](https://arxiv.org/abs/2411.12258)
