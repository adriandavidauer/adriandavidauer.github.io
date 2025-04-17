---
permalink: /phd-research/
title: "Masterplan to PhD"
author_profile: true
---

## Research Focus

My PhD research focuses on **Human-Robot Interaction (HRI)**, specifically on improving **Human-Robot Conversations (HRC)** through visual models. The goal is to enhance **Visual Voice Activity Detection (VVAD)** and **Speaker Identification** to make them robust and applicable in HRI scenarios. This involves addressing several dimensions:

- Transitioning from **single-person** to **multi-person** interactions.
- Exploring input sizes, ranging from:
  - **Lip Features** -> **Face Features** -> **Lip Images** -> **Face Images**  -> **Full Images**.
- Producing outputs such as:
  - **Speaking/Not Speaking Labels** and
  - **Bounding Boxes** for active speakers.

## Research Pillars

My PhD research is structured around three main pillars:

### <span style="color:blue;">1. Data</span>
This pillar focuses on the **VVAD-LRS3 dataset**, which I have created, and the associated pipelines for working with the data. These pipelines ensure efficient data preprocessing, augmentation, and management to support robust model training.

### <span style="color:green;">2. Models</span>
This pillar involves the development and training of models using the VVAD-LRS3 dataset. It also includes the algorithms for pre- and post-processing, as well as the implementation efforts to make these models accessible. This includes:
- Optimized training pipelines.
- Scalable and efficient model architectures.
- Tools and libraries to facilitate easy integration.

### <span style="color:red;">3. Application</span>
This pillar focuses on the **use cases** where the models are applied. It includes conducting experiments to validate the models in real-world scenarios and exploring their utility in various Human-Robot Interaction (HRI) contexts.

## Motivation

I believe it is crucial for humans to interact with robots in a natural way in the future. Currently, Human-Robot Conversations are highly one-dimensional, often resembling simple chatbots. However, the physical form, sensors, and actuators of robots allow for the integration of additional modalities, which can significantly enhance the interaction experience.

## Goals

The primary goal of my PhD is to make **VVAD** and **Speaker Identification** not only robust but also practical for robotics applications. This includes:

1. Developing models that are efficient and scalable:
   - Creating smaller versions of the models that can run on less powerful hardware, beyond high-performance GPUs.
2. Providing accessible implementations:
   - Publishing the final implementation as a **Python library**.
   - Offering a **ROS2 Node** to make the results easily available for robotic systems.
   - Packaging the solution as a **Docker container** for out-of-the-box usability.

By achieving these goals, I aim to bridge the gap between cutting-edge research and practical applications in robotics, enabling more natural and multimodal human-robot interactions.

## Publication Plan

### Published Papers

1. **<span style="color:blue;">The VVAD-LRS3 Dataset for Visual Voice Activity Detection</span>**  
   *A. Lubitz, M. Valdenegro-Toro, F. Kirchner*  
   **Awarded with Best Student Paper Award**  
   Published: 2021  
   Presented at: [7th International Conference on Human Computer Interaction Theory and Applications](https://www.scitepress.org/Papers/2023/116129/116129.pdf)
  

2. **<span style="color:green;">A Bayesian Approach to Context-based Recognition of Human Intention for Context-Adaptive Robot Assistance in Space Missions</span>**  
   *A. Lubitz, O. Arriaga, T. Hassan, N. Hoyer, E.A. Kirchner*  
   Published: 2022  
   Presented at: [SpaceCHI 2.0: Human-Computer Interaction for Space](https://www.dfki.de/fileadmin/user_upload/import/12351_lubitz_kimmi_cobabir_2022_-_Adrian_Lubitz.pdf)

3. **<span style="color:green;">Cobair: A Python Library for Context-Based Intention Recognition in Human-Robot-Interaction</span>**  
   *A. Lubitz, L. Gutzeit, F. Kirchner*  
   Published: 2023  
   Presented at: [32nd IEEE International Conference on Robot and Human Interactive Communication](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10309581)

### Planned Papers

1. [**Review Paper: State of the Art of VVAD in HRI**](/review-paper/)

2. [**<span style="color:red;">Impact of VVAD in HRI</span>**](/impact-of-VVAD/)  


3. [**<span style="color:green;">New Models for VVAD</span>**](/new-models/)  

4. [**<span style="color:blue;">Comparison of VVAD Datasets</span>**](/data-comparison/)

5. [**<span style="color:green;">Implementing Multi-Person VVAD</span>**](/multiperson-VVAD-implementation/)


6. [**<span style="color:red;">Experiments with Multi-Person VVAD</span>**](/multiperson-VVAD-experiments/)  

7. [**<span style="color:blue;">A Benchmark for VVAD in HRI </span>**](/benchmark/)


### Possible Side Papers (Could Be Theses)

1. [**<span style="color:blue;">Social Data Analyzer</span>**](/data-analyzer/) 
   

2. [**<span style="color:red;">HelloRic Project Presentation Paper</span>**](/hello-ric/)


### Possible Ideas for a Post-Doc

1. [**<span style="color:green;">Speech Prediction</span>**](/speech-prediction/)
  

2. [**<span style="color:green;">Mind Wandering Detection</span>**](/mind-wandering/)
   