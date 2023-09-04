

<div align="center">
<h1 align="center">
          <img src="https://img.icons8.com/?size=512&id=55494&format=png" width="80" />
        <img src="https://img.icons8.com/?size=512&id=kTuxVYRKeKEY&format=png" width="80" />
<br>Mobile Traffic Prediction with Federated Learning
</h1>
<h3>◦ o Forecast uplink/downlink performance per station </h3>
<h3>◦ Developed with the software and tools listed below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style&logo=Jupyter&logoColor=white" alt="Jupyter" />
<img src="https://img.shields.io/badge/Python-3776AB.svg?style&logo=Python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Markdown-000000.svg?style&logo=Markdown&logoColor=white" alt="Markdown" />
<img src="https://img.shields.io/badge/Numpy-000000.svg?style&logo=Numpy&logoColor=white" alt="Markdown" />
<img src="https://img.shields.io/badge/Scikit-000000.svg?style&logo=Scikitlearn&logoColor=white" alt="Markdown" />
<img src="https://img.shields.io/badge/Tensorflow-000000.svg?style&logo=Tensorflow&logoColor=white" alt="Markdown" />
<img src="https://img.shields.io/badge/Keras-000000.svg?style&logo=Keras&logoColor=white" alt="Markdown" />
<img src="https://img.shields.io/badge/Monai-000000.svg?style&logo=Monai&logoColor=white" alt="Markdown" />

</p>
</div>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Introduction](#-overview)
- [⚙️ Abstract](#-features)
- [🧩 Dataset](#modules)
- [🚀 Getting Started](#-getting-started)
- [👏 Contact](#-contacts)


![image](https://github.com/harshp77/Federated-Learning-based-traffic-prediction-in-5G/assets/76607486/a9dc8d3c-ae88-4be9-bb45-11a514f63419)

## Introduction

Mobile traffic prediction is paramount in empowering 5G mobile networks to carry out intelligent and effective infrastructure planning and management. This project explores the effectiveness of federated learning in predicting mobile traffic patterns using unprocessed and aggregated LTE data from base stations. Unlike conventional methods that rely on centralized data collection, federated learning allows for decentralized model training while addressing privacy, confidentiality, and performance concerns.

## Abstract

Mobile traffic prediction is paramount in empowering 5G mobile networks to carry out intelligent and effective infrastructure planning and management. Base station logging data are the only data that are currently accessible. Thus, there is a need for training techniques for producing accurate predictions that can generalize to fresh observations of various parties. According to conventional methods, measurements from several base stations must be collected, sent to a central location, and then used to perform machine learning operations on the data. Adopting local observations is constrained by privacy, confidentiality, and performance issues for machine learning. Several distributed learning techniques have been put forth to address this issue, but their potential for traffic prediction has not yet been investigated. This work explores how effective federated learning is when applied to unprocessed and aggregated LTE data from base stations for time-series forecasting. We evaluate one-step predictions for three different cities trained with a federated setting on non-iid data. Our findings indicate that pre-processing techniques on base stations increase forecasting accuracy while state-of-the-art aggregators do not outperform straightforward methods. Learning architectures tailored to federated settings also achieve prediction errors equivalent to those in centralized settings.

## 📊 Mathematical Concepts

In this section, we provide a brief overview of the mathematical concepts used in our federated learning approach:

### Federated Averaging Algorithm

Federated Averaging is a key algorithm in federated learning. It involves aggregating model updates from multiple clients while preserving data privacy. The algorithm can be described as follows:

```math
w(t+1) = (Σ_i w_i^{(t)}) / N
```
Where:

w_(t+1) is the updated global model at time (t+1).

w_i^(t) is the local model of client i at time t.

N is the total number of clients.


## Dataset

### Data Collection

The dataset used in this project consists of unprocessed and aggregated LTE data from base stations in three different cities. Due to privacy and confidentiality constraints, the data collection process adopts a federated learning approach.

### Data Visualization

Visualizing the dataset is essential for understanding its characteristics and patterns. Below are some sample visualizations that provide insights into the data:

![image](https://github.com/harshp77/Federated-Learning-based-traffic-prediction-in-5G/assets/76607486/3ddb40fb-0efd-4780-89e7-efa6d97f5217)


![image](https://github.com/harshp77/Federated-Learning-based-traffic-prediction-in-5G/assets/76607486/88af9225-de9a-4dec-acc2-8ea3c4b80f46)


  <!-- Add a brief description of the visualization and its significance -->

![image](https://github.com/harshp77/Federated-Learning-based-traffic-prediction-in-5G/assets/76607486/dc8f0db4-8ac1-4d3a-bda6-a4d2728a0b39)


  <!-- Add a brief description of the visualization and its significance -->

## Results

Our research produced the following key results:

- Federated learning with unprocessed and aggregated LTE data can effectively predict mobile traffic patterns.
- Pre-processing techniques on base station data improve forecasting accuracy.
- State-of-the-art aggregators do not outperform straightforward methods.
- Learning architectures tailored to federated settings achieve prediction errors equivalent to centralized settings.

For detailed results and analysis, please refer to our [paper](paper_link_here). (Available Soon)




<!-- Getting Started -->
## 	:toolbox: Getting Started


### :key: Libraries

To run this project, you will need to add the following Libraries

`Tensorflow`

`Tensorflow_federated`

`carbontracker`

`tornado==4.5.3`

`tf-nightly`

<!-- Run Locally -->
### :running: Run Locally

Clone the project

```bash
  git clone https://github.com/harshp77/Federated-Learning-based-traffic-prediction-in-5G.git
```

Go to the project directory

```bash
  cd Fed
```

Install dependencies

```bash
  pip install -r requirements.txt
```


<!-- Roadmap -->
## :compass: Roadmap

* [x] Create a Baseline Model
* [x] Create a Client Model

<!-- Contact -->
## :handshake: Contact

Your Name - [Harsh Pandey]() - harsh20101@iiitnr.edu.in

Project Link: [https://github.com/harshp77/Federated-Learning-based-traffic-prediction-in-5G/](https://github.com/harshp77/Federated-Learning-based-traffic-prediction-in-5G/)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

