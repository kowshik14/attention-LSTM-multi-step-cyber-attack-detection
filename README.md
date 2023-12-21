# Attention-based RNN architecture for detecting multi-step cyber-attack using PSO metaheuristic
## Abstract
In recent years, the intensive usage of electronic devices called for a greater threat to preventing a massive volume of information generated by billions of users every second. Therefore, ensuring the stability of these data is deemed to be the cornerstone of the field of cyber security. However, the reliability of any cyber security system has often been compromised with the introduction of various malware and intrusive features within the system. To deal with such abnormal characteristics, an Intrusion Detection System (IDS) has played a vital role over the years. Countless work has continuously been performed to make the IDS more effective and reliable than ever. In this paper, an attention-based Recurrent Neural Network (RNN) model has been proposed for detecting various multi-step cyber-attacks in the network. Our classification model comprises a Long Short-Term Memory (LSTM) unit with an Attention layer. A metaheuristic approach, Particle Swarm Optimization (PSO), has been utilized to exploit the most effective and suitable features with a 72.73% reduction rate from the dataset along with reduced computational complexity and time consumption of around three times less as well as improved detection rate by greater than 1%. This proposed method's performance is evaluated against several evaluation metrics and further analyzed against several traditional classifiers. When compared to the corresponding values of different models on the same dataset, experimental results show significantly improved results in different aspects using the proposed approach.

## Overall Work Flow
![image](https://github.com/kowshik14/Attention/assets/97826581/98102af6-99d3-4fd4-b2c2-9db3a4c16d44)

## Implementation
### Data Pre-Processing

* Dimensionality Reduction using PSO
* Data Standardization

### Cyber-attack Detection Model

![attention](https://github.com/kowshik14/Attention/assets/153311023/0bd57fd0-38d8-4a87-9cc3-91d0088d07da)

### Hyperparameter Optimization Methods

* Grid Search Method

  ![hyperparameter](https://github.com/kowshik14/Attention/assets/153311023/bef6567d-608e-4c07-8fef-6cc589c9de56)

  ### Dataset

  MULTI-STEP CYBER-ATTACK DATASET (MSCAD FOR INTRUSION DETECTION)

  * Publicly available at: https://ieee-dataport.org/documents/multi-step-cyber-attack-dataset-mscad-intrusion-detection
  * Can be processed using the same code
 
  ### Code

  https://github.com/kowshik14/Attention/blob/main/MSCAD.ipynb: Code for all the pre-processing, model implementation and hyper parameter 
  tunning

  ### Libraries
   * Python 3.5+
   * Keras 2.1.0+
   * Tensorflow 1.10.0+

 ### Contact-info
 
  Please feel free to contact us for any questions or cooperation opportunities. We will be happy to help.
  * Email : ebtikarim@ece.kuet.ac.bd OR roy1609001@kuet.ac.bd OR pritombiswas005@gmail.com
  * Google Scholar: [Ebti Karim](https://scholar.google.com/citations?user=5ihaOvAAAAAJ&hl=en), [Kowshik Sankar Roy](https://scholar.google.com/citations?user=5ihaOvAAAAAJ&hl=en)https://scholar.google.com/citations?user=5ihaOvAAAAAJ&hl=en, [Pritom Biswas Udas](https://scholar.google.com/citations?user=0kk6HGAAAAAJ&hl=en)https://scholar.google.com/citations?user=0kk6HGAAAAAJ&hl=en
