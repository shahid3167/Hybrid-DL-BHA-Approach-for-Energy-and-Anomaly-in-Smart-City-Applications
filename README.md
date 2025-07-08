# Hybrid Deep Learning-Black Hole Algorithm (DL-BHA) Approach for Energy Efficiency and Anomaly Detection in Smart City Ecosystems
This repository contains resources related to the **A Hybrid Approach Integrating Deep Learning with Black Hole Algorithm for Energy Efficiency and Anomaly Detection in Smart City Ecosystems** and consists of three folders.
**Dataset** This folder contains the dataset utilized in this study.

**Code**: This folder provides two Jupyter Notebook files (.ipynb) that cover the implementation of the data engineering and hybrid DL-BHA approach.

**Figures**: This folder provides most of the results presented in the paper.

A detailed description of the working mechanism, methodology, and results of the research is included within the repository files.


# System Model of the proposed DL-BHA
The system model consists of several functional components, including the smart city environment with embedded IoT devices for various smart city applications. The temporally collected data from these devices is stored in a data storage unit and subsequently utilized by the developed DL-BHA model. The LSTM, used as the deep learning component, analyzes the data patterns and provides energy consumption predictions and anomaly detection to the BHA. The BHA then assists decision-makers and smart city planners in making optimized decisions based on the outputs of the developed model. The underlying mechanism of the LSTM for anomaly detection and energy efficiency is presented in Figure 2.
<p align="center">
<img src= "https://github.com/shahid3167/Hybrid-DL-BHA-Approach-for-Energy-and-Anomaly-in-Smart-City-Applications/blob/main/Figures/SystemModel.jpg" width ="650" height ="600>
<p align="center">
  
  Fig.1.  Architecture of the proposed DL-BHA framework, highlighting key functional modules responsible for data
monitoring, intelligent control, and decision-making in smart city environments.

<p align="center">
<img src= "https://github.com/shahid3167/Hybrid-DL-BHA-Approach-for-Energy-and-Anomaly-in-Smart-City-Applications/blob/main/Figures/LSTMArchitecture.jpg" width ="650" height ="600>
<p align="center">

Fig. 2. Architecture of the LSTM network for anomaly detection and energy efficiency in smart city environments.

# Dataset Description
A detailed of the dataset with 17 distinct features categorized into temporal, IoT device, smart city applicaiton, and malicious indicator, is presented in Table 1.

<p align="center">
<img src= "https://github.com/shahid3167/Hybrid-DL-BHA-Approach-for-Energy-and-Anomaly-in-Smart-City-Applications/blob/main/Figures/Table1.jpg" width ="650" height ="600>
<p align="center">

# Data Eneginnering
A detail of the various correlation matix and features distribution is presented in the following figurs.

<p align="center">
<img src= "https://github.com/shahid3167/Hybrid-DL-BHA-Approach-for-Energy-and-Anomaly-in-Smart-City-Applications/blob/main/Figures/PearsonCorelation.jpg" width ="700" height ="600>
<p align="center">

Fig. 3. Pearson corelation matrix highlighting relationships among the different features of IoT devices and smart city applications

<p align="center">
<img src= "https://github.com/shahid3167/Hybrid-DL-BHA-Approach-for-Energy-and-Anomaly-in-Smart-City-Applications/blob/main/Figures/FeaturesDistributions.jpg" width ="800" height ="650>
<p align="center">

Fig. 4. A representation of the distributions for the different features of IoT devices and smart city applications.

# Results
The results are evaluated through energy efficiency using loss function and R2 and anomaly detection performance using accuracy, precision, recall, and F-measure.
## Energy Efficiency 
First, the underfitting and overfitting of the developed hybrid DL-BHA model are assessed using the loss function and R²-score. Then, a heterogeneity test is performed by incorporating different noise levels (30%, 50%, and 100%), as described in Figures 5 and 6. Subsequently, energy efficiency is evaluated at these different heterogeneity levels, as illustrated in Figure 7. A sensitivity analysis is then conducted using the Bland-Altman plot, as presented in Figure 8. Based on the findings, the energy efficiency trend is evaluated and presented in Figure 9.

