# Awesome OGI [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
<p align = "center">    
<img  src="https://github.com/user-attachments/assets/cd3d5a9f-129d-4f8c-a197-d84fdc78fa98" width="500" />
</p>
Optical Gas Imaging (OGI) has become a key tool in gas leak detection and industrial safety. This curated list includes research papers, tools, frameworks, and tutorials on OGI technology. It covers OGI hardware, software, real-time leak detection, and applications in industries like oil & gas, chemicals, and environmental monitoring. Whether you're looking for the latest studies or tools for deployment, this resource provides essential insights into OGI.

## Table of Contents

- [Papers](#papers)

    - [HardWare & System](#hardware--system)

        - [Real time infrared gas detection based on a modified EMD algorithm](#real-time-infrared-gas-detection-based-on-a-modified-emd-algorithm2009)

        - [Propane gas leak detection by infrared absorption using carbon infraredemitter and infrared camera](#propane-gas-leak-detection-by-infrared-absorption-using-carbon-infraredemitter-and-infrared-camera2011)
        
        - [An Effective Method for Gas-Leak Area Detection and Gas Identification with Mid-Infrared Image](#an-effective-method-for-gas-leak-area-detection-and-gas-identification-with-mid-infrared-image2022)

        - [Detection and tracking of gas plumes in LWIR hyperspectral video sequence data](#detection-and-tracking-of-gas-plumes-in-lwir-hyperspectral-video-sequence-data2024)

    - [Algorithm]()
    
        - [Deep Learning](#deep-learning-based-ogi)

            - [Machine vision for natural gas methane emissions detection using an infrared camera](#machine-vision-for-natural-gas-methane-emissions-detection-using-an-infrared-camera2018)

            - [VideoGasNet: Deep learning for natural gas methane leak classification using an infrared camera](#videogasnet-deep-learning-for-natural-gas-methane-leak-classification-using-an-infrared-camera2022)

            - [Gasformer: A Transformer-based Architecture for Segmenting Methane Emissions from Livestock in Optical Gas Imaging](#gasformer-a-transformer-based-architecture-for-segmenting-methane-emissions-from-livestock-in-optical-gas-imaging2024)

            - [Invisible Gas Detection: An RGB-Thermal Cross Attention Network and A New Benchmark](#invisible-gas-detection-an-rgb-thermal-cross-attention-network-and-a-new-benchmark2024)
            
            - [Improved Background Estimation for Gas Plume Identification in Hyperspectral Images](#improved-background-estimation-for-gas-plume-identification-in-hyperspectral-images2024) 
            
            - [Black carbon plumes from gas flaring in North Africa identified from multi-spectral imagery with deep learning](#black-carbon-plumes-from-gas-flaring-in-north-africa-identified-from-multi-spectral-imagery-with-deep-learning2024)

            - [A lightweight network based on local-global feature fusion for real-time industrial invisible gas detection with infrared thermography](#a-lightweight-network-based-on-local-global-feature-fusion-for-real-time-industrial-invisible-gas-detection-with-infrared-thermography-2024)

            - [LangGas: Introducing Language in Selective Zero-Shot Background Subtraction for Semi-Transparent Gas Leak Detection with a New Dataset](#langgas-introducing-language-in-selective-zero-shot-background-subtraction-for-semi-transparent-gas-leak-detection-with-a-new-dataset-2025)

            - [GasSeg: A lightweight real-time infrared gas segmentation network for edge devices](#gasseg-a-lightweight-real-time-infrared-gas-segmentation-network-for-edge-devices-2025) 

            - [Contrast Gas Detection: Improving Infrared Gas Semantic Segmentation with Static Background](#contrast-gas-detection-improving-infrared-gas-semantic-segmentation-with-static-background-2025)
              
    - [Limit](#limit)
        - [Are Optical Gas Imaging Technologies Effective For Methane Leak Detection?](#are-optical-gas-imaging-technologies-effective-for-methane-leak-detection2016)
        - [Detection limits of optical gas imagers as a function of temperature differential and distance](#detection-limits-of-optical-gas-imagers-as-a-function-of-temperature-differential-and-distance2019)
        - [Detection Limits of Optical Gas Imaging for Natural Gas Leak Detection in Realistic Controlled Conditions](#detection-limits-of-optical-gas-imaging-for-natural-gas-leak-detection-in-realistic-controlled-conditions2020)


## HardWare & System

### Real time infrared gas detection based on a modified EMD algorithm(2009)
- overview:<br>
This paper introduces a novel algorithm for real-time infrared (IR) gas detection based on a modified Empirical Mode Decomposition (EMD) method. The authors propose a modified EMD (m-EMD) algorithm that selectively extracts the intrinsic mode function (IMF) component related to gas concentration, rather than decomposing the entire signal into all possible IMFs. This approach reduces computational complexity and improves detection precision. Additionally, a mean-envelope filtering (MEF) method is introduced to further suppress noise in the amplitude envelope obtained by the m-EMD. The combination of m-EMD and MEF demonstrates higher sensitivity and eliminates the "lagging" effect commonly associated with digital lock-in amplifiers (DLIA), making it suitable for real-time gas detection.

- [paper](https://www.sciencedirect.com/science/article/pii/S0925400508008009)
- code: *not available*
- datasets: *not available*


### Propane gas leak detection by infrared absorption using carbon infraredemitter and infrared camera(2011)
- overview:<br>
This study introduces a propane gas leak detection system based on infrared absorption using a carbon infrared emitter (CIE) and an infrared camera. 
    - The hardware includes a CIE transmitting infrared wavelengths of 1–5 μm, a parabolic reflector for uniform infrared radiation, and a Raytheon-Amber Radiance HS infrared camera equipped with an indium antimonide (InSb) detector. The study uses a bandpass filter centered at 3.37 μm to isolate the absorption band of propane gas. 
    - Infrared intensity changes due to propane absorption are analyzed to create real-time images of gas leaks. The algorithm correlates the intensity and concentration-pathlength product to evaluate hazards.

- [paper](https://www.sciencedirect.com/science/article/pii/S0963869510001143)
- code: *not available*
- datasets: *not available*

### An Effective Method for Gas-Leak Area Detection and Gas Identification with Mid-Infrared Image(2022)
- overview:<br>
This study presents an effective method for gas-leak area detection and gas identification using a mid-infrared imaging system. 
    - The hardware employs a broadband uncooled infrared focal-plane detector, covering both mid-wave and long-wave bands, equipped with a rotating filter wheel and image-processing module for multi-spectral imaging. 
    - The system is capable of capturing real-time gas leakages under various conditions. The proposed algorithm combines an advanced image-enhancement technique using Gaussian filtering and adaptive histogram segmentation with an improved ViBe background subtraction method to detect gas leakage areas dynamically.

- [paper](https://www.mdpi.com/2304-6732/9/12/992)
- code: *not available*
- datasets: *not available*

### Detection and tracking of gas plumes in LWIR hyperspectral video sequence data(2024)

- overview:<br>
This paper presents a method for detecting and segmenting chemical gas plumes in LWIR hyperspectral video sequences. It addresses challenges in plume segmentation due to its diffusive nature and invisibility in standard RGB imagery. The proposed approach combines Principal Component Analysis (PCA) for dimensionality reduction, Midway histogram equalization for frame smoothing, and clustering techniques (K-means, spectral clustering, and a modified MBO scheme) for segmentation. Results demonstrate the effectiveness of these methods in isolating gas plumes, with the modified MBO scheme achieving the best performance.

    - Data Processing Pipeline:<br>
        - Dimensionality Reduction (PCA):
    Principal Component Analysis (PCA) is used to reduce the high-dimensional hyperspectral data, focusing on the most informative components to create a false-color RGB representation.
        - Histogram Equalization (Midway Method):
    Midway histogram equalization smooths intensity variations across video frames, reducing flicker and improving frame-to-frame continuity.

    - Clustering Techniques for Segmentation:
        - K-means Clustering: Applied with Euclidean and cosine distance metrics, K-means effectively separates plume regions but can suffer from initialization sensitivity.
        - Spectral Clustering: Utilizes eigenvalues of the graph Laplacian to form clusters. Feature vectors enhance segmentation quality.
        - Modified MBO Scheme: A semi-supervised method based on minimizing the Ginzburg-Landau functional for refined segmentation of gas plumes.

- [paper](https://arxiv.org/pdf/2411.00281)
- code: *not available*
- datasets: *not available*



## Deep Learning based OGI:

### Machine vision for natural gas methane emissions detection using an infrared camera(2018)

- overview:<br>
This paper introduces a novel approach for detecting methane emissions using an infrared camera and a deep learning-based system, GasNet. 
    - The hardware includes the FLIR GF320 infrared camera and a controlled experimental facility with various leak sources. The study leverages a labeled video dataset, GasVid, which captures methane leaks at different flow rates and imaging distances. 
    - The algorithm uses convolutional neural networks (CNNs) to identify methane plumes through background subtraction and feature extraction. 
- [paper](https://www.sciencedirect.com/science/article/pii/S030626191931685X)
- code: *not available*
- datasets: *not available*

### VideoGasNet: Deep learning for natural gas methane leak classification using an infrared camera(2022)

- overview:<br>
This study introduces VideoGasNet, a 3D CNN-based deep learning model for methane leak classification using infrared video data. 
    - The hardware includes a FLIR GF320 infrared camera capturing the GasVid dataset, which contains labeled methane leak videos under controlled release conditions. 
    - The system integrates video pre-processing techniques like background subtraction and leverages temporal information across frames for enhanced accuracy. 
    - The model achieves nearly 100% binary classification accuracy and 78.2% for small-medium-large leak size classification, showcasing its capability to extend OGI systems from detection to automated classification.

- [paper](https://www.sciencedirect.com/science/article/pii/S0360544221017643)
- code: *not available*
- datasets: *not available*

### Gasformer: A Transformer-based Architecture for Segmenting Methane Emissions from Livestock in Optical Gas Imaging(2024)

- overview:<br>
This study presents Gasformer, a novel Transformer-based architecture for semantic segmentation of methane emissions in optical gas imaging. 
    - The hardware employs the FLIR GF77 optical gas imaging camera to capture two unique datasets: a controlled methane release dataset and a dairy cow rumen gas dataset. 
    - The research integrates a Mix Vision Transformer encoder to extract multi-scale features and a Light-Ham decoder for refining segmentation maps. The algorithm leverages advanced self-attention mechanisms and matrix decomposition to achieve accurate segmentation. 

- [paper](https://openaccess.thecvf.com/content/CVPR2024W/Vision4Ag/html/Sarker_Gasformer_A_Transformer-based_Architecture_for_Segmenting_Methane_Emissions_from_Livestock_CVPRW_2024_paper.html)
- [code](https://github.com/toqitahamid/Gasformer)
- datasets: *not available*

### Invisible Gas Detection: An RGB-Thermal Cross Attention Network and A New Benchmark(2024)

- overview:<br>
This study introduces RT-CAN (RGB-Thermal Cross Attention Network), a novel two-stream architecture designed for detecting vision-invisible gases. 
    - The hardware includes an RGB camera and a thermal infrared camera with pixel-level alignment for capturing the Gas-DB dataset, comprising 1,293 well-annotated RGB-thermal image pairs across eight diverse scenarios. 
    - This study leverages the RGB-assisted Cross Attention (RCA) module to enhance thermal feature learning by fusing RGB and thermal modalities, while the cascaded decoder with Global Textural Attention (GTA) modules ensures precise pixel-level segmentation.
    - RT-CAN achieves state-of-the-art performance, improving IoU, accuracy, and F2 scores over existing models by 5.65%, 4.86%, and 4.88%, respectively, demonstrating its effectiveness for gas detection in complex environments.

- [paper](https://arxiv.org/abs/2403.17712)
- [code](https://github.com/logic112358/RT-CAN)
- [datasets](https://drive.google.com/drive/folders/11t324MSRVQhptfLLu65MlPaSaPOJRf4Z?usp=sharing) 

### Improved Background Estimation for Gas Plume Identification in Hyperspectral Images(2024)
- overview<br>
This paper explores the improvement of background estimation methods to enhance the recognition performance of gas plumes in long-wave infrared hyperspectral images. 
    - The purpose of the study is to determine which method can most accurately estimate the background radiation below the plume and improve the confidence level of the neural network in recognizing the gas.
    - The paper proposes two new methods, K-Nearest Segments (KNS) and K-Nearest Neighbors (KNN), and compares them with three existing methods: PCA, KMeans, and the ring-band method. 
    - It was found that PCA performed the best in background estimation. However, KNS performed best in improving the confidence of the neural network in recognizing gases that are difficult to identify, such as C2H2 and N2O. The paper also explores the sensitivity of the different methods to hyperparameters and finds that KNN and PCA are insensitive to hyperparameters, while KNS and the ring-band method require more tuning.
    - The paper tests these methods by simulating 640 plumes with different gases and signal strengths, and shows that PCA, while having the best background estimation, does not directly translate into better identification confidence, possibly because it is a global method that does not handle local variations well. Future work may need to explore local covariance estimation and test the performance of these methods on real data.


- [paper](https://arxiv.org/pdf/2411.15378)
- code: *not available*
- datasets: *not available*

### Black carbon plumes from gas flaring in North Africa identified from multi-spectral imagery with deep learning(2024)

- overview<br>
This study introduces a deep learning framework for detecting and quantifying black carbon (BC) plumes from gas flaring using Sentinel-2 multi-spectral satellite imagery.
    - The hardware includes the Sentinel-2 satellite, which provides high-resolution multi-spectral imagery, including RGB and infrared bands, used to identify gas flares and BC plumes.
    - This study integrates traditional flare-identification algorithms (e.g., Normalized Hotspot Indices and Thermal Anomaly Index) with a ConvLSTM deep learning model to detect BC plumes. Synthetic BC plumes are generated using a custom 2D LES plume model for training the deep learning model.
    - The model achieves high accuracy in detecting BC plumes, particularly for large plumes, and estimates BC emissions using the Integrated Mass Enhancement (IME) method. The study estimates that BC emissions from gas flaring in North Africa in 2022 amounted to 6.2 Gg, with Algeria contributing 75% of the total.

- [paper](https://arxiv.org/pdf/2406.06183)
- code: *not available*
- datasets: *not available*

### A lightweight network based on local-global feature fusion for real-time industrial invisible gas detection with infrared thermography (2024)

   - overview
        - This research introduces GasViT, a novel lightweight network specialized for detecting industrial invisible gases in thermal images by fusing local and global features. The model is designed to overcome challenges posed by indistinct gas features and the high computational cost of existing methods.

        - The paper presents the Industrial Invisible Gas (IIG) Dataset, a self-made collection of 5,569 thermal images containing 11,186 gas leakage instances across five different industrial scenarios.

        - The architecture features two new modules: the Multi-scale Fusion Feature Attention (MsFFA), which enhances local feature extraction , and the Multi-head Linear Self-attention (MhLSa), which efficiently encodes global information at a low computational cost.

        - GasViT achieves 82.7% mAP50 on the IIG dataset, outperforming other state-of-the-art lightweight networks. It can be deployed on edge devices, reaching 33 FPS with a memory footprint of only 47.2 MB, making it highly suitable for portable and embedded detection systems.


- [paper](https://doi.org/10.1016/j.asoc.2023.111138)

- code: *Not publicly available*.

- datasets: *Not publicly available; the paper states, "Data will be made available on request"*.


### LangGas: Introducing Language in Selective Zero-Shot Background Subtraction for Semi-Transparent Gas Leak Detection with a New Dataset (2025)
- overview<br>
    - Used Background Subtraction with Vision Langugae Model to detect leakage
    - Used SAM 2 to segment the leakage
    - Tested on a computer-rendered dataset

- [paper](https://arxiv.org/abs/2503.02910)
- [dataset](https://paperswithcode.com/dataset/simgas)
- [code](https://github.com/weathon/Lang-Gas)

### GasSeg: A lightweight real-time infrared gas segmentation network for edge devices (2025)
- overview<br>

    - This paper proposes GasSeg, a lightweight, dual-branch neural network designed for real-time infrared gas segmentation (IGS) on edge computing devices. Its purpose is to identify gas regions within infrared images to aid in leakage prevention and detection.

    - To facilitate research, the authors introduce a high-quality, real-world IGS dataset containing 6,426 images and 7,390 gas segmentation annotations collected from authentic industrial scenarios.

    - Key technical innovations include a Boundary-Aware Stem (BA Stem) to improve sensitivity to gas shapes , a dual-branch architecture where a boundary guidance branch refines a context branch , and a Contextual Attention Pyramid Pooling Module (CAPPM) to capture essential global features.

    - GasSeg demonstrates state-of-the-art performance, achieving 90.68% mIoU and 95.02% mF1, with inference speeds of 215 FPS on a GPU and 62 FPS on an edge platform, making it suitable for real-world industrial applications.


 - [paper](https://doi.org/10.1016/j.patcog.2025.111931)
 - [code](https://github.com/FisherYuuri/GasSeg)
 - [datasets](https://github.com/FisherYuuri/GasSeg)

### Contrast Gas Detection: Improving Infrared Gas Semantic Segmentation with Static Background (2025)

- overview

    - This paper introduces a novel approach for infrared gas semantic segmentation by leveraging static background information to improve accuracy. The proposed model, CGNet, is designed specifically for gas leakage scenarios.

    - A new annotation methodology is presented, which involves differencing gas leakage images from their corresponding static backgrounds to precisely delineate leakage areas.

    - Based on this method, the Contrast Gas Detection (CGD) dataset was created, containing 926 static background-gas image pairs from 38 video sequences. The dataset is categorized by release distance, amount, and gas type (SF6, CF4, and Water).

    - The proposed model, CGNet, uses a Gas Contrast Attention (GCA) mechanism to compare features from the static background and the gas scene, which are processed by a ResNet backbone. It outperforms other widely used semantic segmentation models on the CGD dataset, with improvements of 5.83% in Accuracy, 5.57% in IoU, and 5.00% in FScore.

- [paper](https://arxiv.org/pdf/2404.04018)

- [code](https://github.com/ProAlize/CGNet) 

- [datasets](https://github.com/ProAlize/CGNet) 




## Limit

### Are Optical Gas Imaging Technologies Effective For Methane Leak Detection?(2016)
- overview<br>
This study investigates the detection limits of Optical Gas Imaging (OGI) technology for detecting natural gas leaks in realistic controlled conditions. 
    - Conducted at Colorado State University's Methane Emissions Technology Evaluation Center (METEC), the research examines the impact of hardware performance, environmental factors, and human factors on the efficiency of OGI leak detection.
    - The study utilizes the FLIR GF320 infrared camera, operating in the 3.2–3.4 μm spectral band, to capture methane emissions from controlled leakage points at varying flow rates. 
    - Surveyor experience significantly influences detection rates, with highly experienced surveyors detecting 1.7 times more leaks than those with less experience. The findings underscore the importance of background contrast, wind speed, and survey protocol in optimizing detection performance.

- [paper](https://pubs.acs.org/doi/full/10.1021/acs.est.6b03906)

### Detection limits of optical gas imagers as a function of temperature differential and distance(2019)

- overview:<br>
This paper investigates the detection limits of Optical Gas Imaging (OGI) as a function of temperature differential ($\Delta T$) and distance, providing quantitative models to predict OGI detection limits under varying temperature differentials and distances.
    - Optical Gas Imaging (OGI) Contrast Equation:<br>
        
        $$\Delta I = \left[ B(T_B, \lambda) - B(T_G, \lambda) \right] \cdot \left[ 1 - \exp(-\alpha(\lambda)CL) \right] \cdot t(\lambda)$$
    
    - Detection Limit versus Temperature Difference:<br>
        
        $$DL_{\text{ppm-m}} = \alpha \cdot |\Delta T|^{\beta}$$
    
    - Detection limit (g/h) versus distance and temperature difference:<br>
        
        $$DL_{\text{gph}} = c \cdot DL_{\text{ppm-m}} \cdot d^2 \cdot w \cdot \frac{P}{T} \cdot \frac{\text{MW}}{R}$$
    
    - Simplified mass flow rate detection limit equation:<br>
        When using a FLIR GF320 camera with a 23 mm lens and assuming normal diffusion conditions, the mass flow rate detection limit can be simplified to:<br>
        
        $$DL_{\text{gph}} = 18.41 \cdot |\Delta T|^{-1.094} \cdot d^2$$
    
    - Comparison of detection limits for absorptive and radiative plumes:<br>
        Ratio of detection limits for absorptive and radiative plumes at the same absolute temperature difference ($\Delta T$):<br>
        for methane:<br>
        
        $$\frac{DL_{\text{ppm-m, absorption}}}{DL_{\text{ppm-m, radiant}}} \approx 1.19 \, \text{to} \, 2.55$$
        
        for propane:<br>
        
        $$\frac{DL_{\text{ppm-m, absorption}}}{DL_{\text{ppm-m, radiant}}} \approx 1.11 \, \text{to} \, 2.35$$
    
    - Calculation of the maximum permissible detection distance:<br>
        If the target detection limit is set (e.g. 30 g/h), the maximum permissible detection distance is calculated according to the temperature difference $\Delta T$, the maximum permissible detection distance is calculated:<br>
        
        $$d_{\text{max}} = \sqrt{\frac{DL_{\text{gph}}}{c_1 \cdot |\Delta T|^{-1.094}}}$$
        

- [paper](https://www.tandfonline.com/doi/abs/10.1080/10962247.2018.1540366)


### Detection Limits of Optical Gas Imaging for Natural Gas Leak Detection in Realistic Controlled Conditions(2020)

- overview:<br>
The study identifies the critical roles of hardware, environmental conditions, and human factors in influencing detection efficiency.
    - The hardware employs the FLIR GF320 optical gas imaging camera, which operates in the 3.2–3.4 μm infrared spectral band, to capture controlled methane gas emissions under realistic outdoor conditions.
    - The system includes a multi-faceted testing setup at the METEC facility, featuring three simulated well pads. Controlled solenoid valves and Omega FMA-1700 thermal mass flow meters precisely regulate and measure gas emission rates. Environmental variables, such as wind speed, temperature, and background types (e.g., ground, equipment, and sky), are integrated into the system to assess detection performance under varying conditions.

- [paper](https://pubs.acs.org/doi/abs/10.1021/acs.est.0c01285)




continue updating...







