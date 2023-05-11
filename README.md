# Leak Detection and Localization in Water Distribution Networks using Graph Neural Networks

**Authors:** Rodrigo P. Rolle, Lucas R. Tomazini, Lucas N. Monteiro, Eduardo P. Godoy, Alexandre A. Simões

This repository contains the code for the article titled "Leak Detection and Localization in Water Distribution Networks using Graph Neural Networks". The article addresses the problem of distributed monitoring of water distribution networks, with a focus on leakage detection and localization. The study utilizes Gated Graph Graph Neural Networks [(GNNs)](https://arxiv.org/abs/1511.05493), a type of Deep Learning algorithm capable of processing graph-structured data.

## Abstract
Management of water resources has been one of the biggest concerns of the XXIst Century, drawing the attention of global initiatives such as the Sustainable Development Objectives of the United Nations. This work approaches the problem of distributed monitoring of water distribution networks focusing on leakage detection and localization, using Gated Graph Neural Networks, which are Deep Learning algorithms capable of processing graph-structured data. Thus, the spatial displacement of the measurement points is also part of the calculations, alongside the measurement data itself. Software models of water distribution networks were implemented in a software environment for data collection in diverse operation scenarios, especially leakages in different locations. Two hypothetical water distribution networks were created for the study and evaluation of the algorithm’s capabilities. The results demonstrate that the graph-based approach is a viable methodology for the detection and location of water leakages, especially considering the restrictions of data transmission rates.


<p align="center">
  <img src="/WDN_mapping.png" alt="WDN mapping" width="600" height="400">
  <figcaption style="text-align: center;">Legenda da Imagem</figcaption>
</p>

<p align="center">
  <img src="/Probability.png" alt="Probability distribution outputed by Gated Graph Neural Network (GGNN)" width="600" height="400">
</p>



## Introduction
Water distribution networks (WDNs) play a crucial role in managing water resources efficiently. This article presents a leak detection and location method for WDNs based on GNNs. The method incorporates the characteristics of the network, such as node interconnections and layout, into the Machine Learning (ML) algorithm, mitigating the challenges of having sparse measurement data. The research uses the EPANET software to simulate water distribution networks and implements the leak detection algorithm using the Gated Graph Neural Network (GGNN) architecture.





## License
This project is licensed under the MIT License. See the LICENSE file for details.


