# Attention-based RNN Architecture for Detecting Multi-Step Cyber-Attack Using PSO Metaheuristic

![Python](https://img.shields.io/badge/Python-3.5+-blue.svg?style=for-the-badge&logo=python&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-2.1.0+-D00000?style=for-the-badge&logo=keras&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-1.10.0+-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

## Abstract
In recent years, the intensive usage of electronic devices has increased threats to the stability of massive amounts of information generated by billions of users every second. To counter such threats, an **Intrusion Detection System (IDS)** plays a key role. In this paper, an attention-based Recurrent Neural Network (RNN) model is proposed for detecting multi-step cyber-attacks in networks. Our model combines **Long Short-Term Memory (LSTM)** units with an **Attention layer** and employs **Particle Swarm Optimization (PSO)** for feature selection, resulting in a 72.73% reduction in features and a 3x reduction in computational time while improving detection rates by over 1%. The model outperforms traditional classifiers on the same dataset, showing improved results across multiple metrics.

## Read the Full Paper
📄 [IEEE Xplore](https://doi.org/10.1109/ECCE57851.2023.10101590)
📄 [Research Gate](https://www.researchgate.net/publication/370131834_Attention-based_RNN_architecture_for_detecting_multi-step_cyber-attack_using_PSO_metaheuristic)

---

## Overall Workflow

![Workflow](https://github.com/kowshik14/Attention/assets/97826581/98102af6-99d3-4fd4-b2c2-9db3a4c16d44)

---

## Implementation

### Data Pre-Processing

- **Dimensionality Reduction:** Particle Swarm Optimization (PSO)
- **Data Standardization**

### Cyber-Attack Detection Model

![Attention-based RNN](https://github.com/kowshik14/Attention/assets/153311023/0bd57fd0-38d8-4a87-9cc3-91d0088d07da)

---

## Hyperparameter Optimization

### Grid Search Method

![Hyperparameter Tuning](https://github.com/kowshik14/Attention/assets/153311023/bef6567d-608e-4c07-8fef-6cc589c9de56)

---

## Dataset

**Multi-Step Cyber-Attack Dataset (MSCAD for Intrusion Detection)**

- Publicly available at: [MSCAD Dataset](https://ieee-dataport.org/documents/multi-step-cyber-attack-dataset-mscad-intrusion-detection)
- Can be processed using the provided code.

---

## Code

Find the full implementation, including pre-processing, model development, and hyperparameter tuning in this notebook:

📂 [MSCAD.ipynb](https://github.com/kowshik14/Attention/blob/main/MSCAD.ipynb)

---

## Libraries

This project uses the following libraries:

![Python](https://img.shields.io/badge/Python-3.5+-blue.svg?style=flat-square&logo=python&logoColor=white)  
![Keras](https://img.shields.io/badge/Keras-2.1.0+-D00000?style=flat-square&logo=keras&logoColor=white)  
![TensorFlow](https://img.shields.io/badge/TensorFlow-1.10.0+-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

---

## Contact Info

For any questions or collaboration opportunities, feel free to contact us:

- **Email:**  
  📧 ebtikarim@ece.kuet.ac.bd  
  📧 kowshikroy777@gmail.com  
  📧 pritombiswas005@gmail.com

- **Google Scholar Profiles:**  
  [Ebti Karim](https://scholar.google.com/citations?user=5ihaOvAAAAAJ&hl=en)  
  [Kowshik Sankar Roy](https://scholar.google.com/citations?user=5ihaOvAAAAAJ&hl=en)  
  [Pritom Biswas Udas](https://scholar.google.com/citations?user=0kk6HGAAAAAJ&hl=en)

---

## Citation

If you find this repository useful in your research, please cite our work:

```bibtex
@inproceedings{udas2023attention,
  title={Attention-based RNN architecture for detecting multi-step cyber-attack using PSO metaheuristic},
  author={P. B. Udas, K. S. Roy, M. E. Karim, and S. M. Azmat Ullah},
  booktitle={2023 International Conference on Electrical, Computer and Communication Engineering (ECCE)},
  year={2023},
  doi={10.1109/ECCE57851.2023.10101590}
}
