# Adversarial attack defense analysis: An empirical approach in cybersecurity perspective 
This repository comprises the project's "Adversarial attack defense analysis: An empirical approach in cybersecurity perspective'. The code and presented model can be utilized in Cybersecurity  anomaly detection against adversarial attack scenarios.

This presented study explores the susceptibility of the DL-based technique against two adversarial attack techniques, i.e., Limited-memory BFGS  and DeepFool. The study illustrates a DL-based defense technique, i.e., a combined RNN and LSTM optimization defense mechanism to counter adversarial attacks. RobustScaler is utilized in preprocessing, and Linear Discriminant Analysis is employed in feature extraction. It uses four LSTM architecture layers, i.e., Layer 1, Layer 2, Layer 3, and Layer 4. The Grey Wolf Optimization (GWO)  is used to fine-tune the LSTM model's hyperparameters to achieve better optimization performance, and RNN is used as a source of LSTM layers. Transferability learning is used to the model's robustness when subjected to adversarial attacks, such as those generated by the DeepFool and Limited-memory BFGS methods. This process involves creating adversarial examples, inputs designed to deceive the model into making incorrect predictions. The Adam optimizer is known for its significance in addressing sparse gradients on noisy data. The loss function utilized is absolute cross-entropy, suitable for forecast studies where the model predicts probabilities across multiple classes. The pre-trained model is tested against these adversarial examples to evaluate its resilience and robustness. This step is vital for understanding the model's security and reliability in real-world applications where adversarial attacks could be a threat. The model's outcome is evaluated using a testing dataset.


Three papers have been published in this project:

Barik, K., Misra, S., Konar, K., Fernandez-Sanz, L., & Koyuncu, M. (2022). Cybersecurity deep: Approaches, attacks dataset, and comparative study. Applied Artificial Intelligence, 36(1), https://doi.org/10.1080/08839514.2022.2055399.

Barik, K., Misra, S. & Fernandez-Sanz, L. Adversarial attack detection framework based on optimized weighted conditional stepwise adversarial network. Int. J. Inf. Secur. (2024). https://doi.org/10.1007/s10207-024-00844-w

https://github.com/kousikbarik/WSCAN-PSO

Barik, K., & Misra, S. (2024). IDS-Anta: An open-source code with a defence mechanism to detect adversarial attacks for intrusion detection system. Software Impacts, 100664.
https://doi.org/10.1016/j.simpa.2024.100664

https://github.com/kousikbarik/lab-ids-anta/tree/main

# Abstract

Advancements in artificial intelligence in the cybersecurity domain introduce significant security challenges. A critical concern is the exposure of deep learning techniques to adversarial attacks. Adversary users intentionally attempt to mislead the techniques by infiltrating adversarial samples during the training or testing phase to mislead the prediction of security devices. The study presents extensive experimentation of defense methods using Python-based open-source code with two benchmark datasets, and the outcomes are demonstrated using evaluation metrics. This code library can be easily utilized and reproduced for cybersecurity research on countering adversarial attacks. Exploring strategies for defending against adversarial attacks is significant in enhancing the resilience of deep learning techniques.

# #Research Questions

•	How can LSTM architecture layer optimization be performed, and can RNN be used as a source of LSTM layers, a useful classifier, and improve the attack detection rate? 

•	How can DeepFool and Limited-memory BFGS be employed to develop adversarial attacks?

•	What is the importance of transfer learning in adversarial attacks? 

•	What techniques can be used to enhance the ability of DL models to identify adversarial attacks by combining hybrid defense techniques?

# An outline of the proposed model
![1 jpeg](https://github.com/kousikbarik/Adversarial-attack-defense-analysis/assets/91803246/24fa75b4-efd3-439c-8c9d-9a4c82ec77b6)


Fig. 1. An outline of the proposed model

# Architecture of the proposed model 

![image](https://github.com/kousikbarik/Adversarial-attack-defense-analysis/assets/91803246/ae1aa757-e986-4341-aa3b-7adae6dbfcc0)

Fig. 2. Architecture of the proposed model 


**#Dataset**
The CIC-IDS-2017 is a popular publicly available dataset for IDS. (https://www.unb.ca/cic/datasets/ids-2017.html)

The CSE-CIC-IDS2018 is a publicly available dataset for IDS.(https://www.unb.ca/cic/datasets/ids-2018.html)

**#Code**

Limited-memory BFGS_2017.ipynb

Deepfool_2017.ipynb

Limited-memory BFGS_2018.ipynb 

Deepfool_2018.ipynb


**# Algorithims**

Linear Discriminant Analysis (LDA)

Grey Wolf Optimization (GWO)

Long short-term memory (LSTM)

Recurrent Neural Network (RNN)

