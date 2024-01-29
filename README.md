# Light Weight-Federated-Learning-Approach-towards-Smart-Energy-Meter-Dataset

This project is part of Msc Thesis at Trinity College Dublin. 

The project focuses on simulating a Federated Learning framework using the London Household smart energy meter dataset. The primary objective is to achieve comparable accuracy in load forecasting to state-of-the-art (SOTA) technologies while demonstrating the preservation
of data privacy through FL. In real-world scenarios, the challenge of non-i.i.d. connections persists. To replicate real-world conditions, limited random connections are considered for each round of FL. Additionally, since smart meters often have limited computational
power, small sequential dense neural networks (DNN) are utilized to address this constraint. These DNN models are well-suited for low computational power devices and contribute to solving the computational challenges posed by smart meters. Through
this project, the aim is to showcase the potential of FL in maintaining data privacy while achieving accurate load forecasting results, even in resource-constrained environments.

Brief on the Project : ((https://ieeexplore.ieee.org/abstract/document/10333889))

The simulation is performed using Tensorflow Federated Libraries and Framework. To install TFF refer https://www.tensorflow.org/federated/install

Dataset Information : https://data.london.gov.uk/dataset/?q=energy

For further research, 
Cite : A. Duttagupta, J. Zhao and S. Shreejith, "Exploring Lightweight Federated Learning for Distributed Load Forecasting," 2023 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm), Glasgow, United Kingdom, 2023, pp. 1-6, doi: 10.1109/SmartGridComm57358.2023.10333889.
keywords: {Meters;Training;Energy consumption;Data privacy;Load forecasting;Federated learning;Predictive models;Federated learning;deep neural networks;Non - i.i.d distribution;data heterogeneity}, 

## Code

The Code is divided into 5 parts
1) Data Cleaning and K - Means Application : <Code\datacl_kmeans_final.ipynb>
2) Short Term Daily Analysis code with custom loss function (MAIN CODE) : <Code\Short_Term_FC_custom_LF.ipynb>
3) Custom TFF Algorithms for checking Global and Local Weights : <Code\Customized_TFF_Functionalities.ipynb> 
4) Weekly Analysis Code : <Code\Weekly_Analysis.ipynb>
5) Monthly Analysis Code : <Code\Monthly_Analysis.ipynb>
6) Centralized Model Code : <Code\Centralized_model.ipynb>   

