# Awesome OGI [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
<p align = "center">    
<img  src="https://github.com/user-attachments/assets/cd3d5a9f-129d-4f8c-a197-d84fdc78fa98" width="500" />
</p>
Optical Gas Imaging (OGI) has become a key tool in gas leak detection and industrial safety. This curated list includes research papers, tools, frameworks, and tutorials on OGI technology. It covers OGI hardware, software, real-time leak detection, and applications in industries like oil & gas, chemicals, and environmental monitoring. Whether you're looking for the latest studies or tools for deployment, this resource provides essential insights into OGI.

## Table of Contents

- [Papers](#papers)
    - [HardWare & System](#hardware--system)
        - [An Effective Method for Gas-Leak Area Detection and Gas Identification with Mid-Infrared Image](#an-effective-method-for-gas-leak-area-detection-and-gas-identification-with-mid-infrared-image)
        - [Propane gas leak detection by infrared absorption using carbon infraredemitter and infrared camera]()
    - [Algorithm]()
    
        - [Deep Learning](#deep-learning-based-ogi)
            - [Machine vision for natural gas methane emissions detection using an infrared camera](#machine-vision-for-natural-gas-methane-emissions-detection-using-an-infrared-camera2018)    
            
            - [Gasformer: A Transformer-based Architecture for Segmenting Methane Emissions from Livestock in Optical Gas Imaging](#gasformer-a-transformer-based-architecture-for-segmenting-methane-emissions-from-livestock-in-optical-gas-imaging2024)
            
            - [Invisible Gas Detection: An RGB-Thermal Cross Attention Network and A New Benchmark](#invisible-gas-detection-an-rgb-thermal-cross-attention-network-and-a-new-benchmark2024)
            
            - [VideoGasNet: Deep learning for natural gas methane leak classification using an infrared camera](#videogasnet-deep-learning-for-natural-gas-methane-leak-classification-using-an-infrared-camera2022)

## HardWare & System
### An Effective Method for Gas-Leak Area Detection and Gas Identification with Mid-Infrared Image
- overview:
- [paper](https://www.mdpi.com/2304-6732/9/12/992)
- code: not available
- datasets: not available

### Propane gas leak detection by infrared absorption using carbon infraredemitter and infrared camera
- overview: 
This study introduces a propane gas leak detection system based on infrared absorption using a carbon infrared emitter (CIE) and an infrared camera. 
    - The hardware includes a CIE transmitting infrared wavelengths of 1–5 μm, a parabolic reflector for uniform infrared radiation, and a Raytheon-Amber Radiance HS infrared camera equipped with an indium antimonide (InSb) detector. The study uses a bandpass filter centered at 3.37 μm to isolate the absorption band of propane gas. 
    - Infrared intensity changes due to propane absorption are analyzed to create real-time images of gas leaks. The algorithm correlates the intensity and concentration-pathlength product to evaluate hazards.

- [paper](https://www.sciencedirect.com/science/article/pii/S0963869510001143)
- code: not available
- datasets: not available

## Deep Learning based OGI:

### Machine vision for natural gas methane emissions detection using an infrared camera(2018)
- overview: 
This paper introduces a novel approach for detecting methane emissions using an infrared camera and a deep learning-based system, GasNet. 
    - The hardware includes the FLIR GF320 infrared camera and a controlled experimental facility with various leak sources. The study leverages a labeled video dataset, GasVid, which captures methane leaks at different flow rates and imaging distances. 
    - The algorithm uses convolutional neural networks (CNNs) to identify methane plumes through background subtraction and feature extraction. 
- [paper](https://www.sciencedirect.com/science/article/pii/S030626191931685X)
- code: not available
- datasets: not available

### VideoGasNet: Deep learning for natural gas methane leak classification using an infrared camera(2022)

- overview:
- [paper](https://www.sciencedirect.com/science/article/pii/S0360544221017643)
- code: not available
- datasets: not available

### Gasformer: A Transformer-based Architecture for Segmenting Methane Emissions from Livestock in Optical Gas Imaging(2024)

- overview:
- [paper](https://openaccess.thecvf.com/content/CVPR2024W/Vision4Ag/html/Sarker_Gasformer_A_Transformer-based_Architecture_for_Segmenting_Methane_Emissions_from_Livestock_CVPRW_2024_paper.html)
- [code](https://github.com/toqitahamid/Gasformer)
- datasets: not available

### Invisible Gas Detection: An RGB-Thermal Cross Attention Network and A New Benchmark(2024)

- overview:
- [paper](https://arxiv.org/abs/2403.17712)
- [code](https://github.com/logic112358/RT-CAN)
- [datasets](https://drive.google.com/drive/folders/11t324MSRVQhptfLLu65MlPaSaPOJRf4Z?usp=sharing) 





continue updating...







