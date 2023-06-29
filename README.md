# Basalt: Robust Federated Learning Framework for Defending Byzantine Attacks in Non-IID Data
Federated learning (FL), an emerging distributed learning paradigm, has been widely employed in data mining to extract valuable information from vast amounts of data. However, the distributed nature of FL makes it susceptible to Byzantine attacks, where malicious attackers can intentionally behave in a malicious manner to cause performance degradation of the global model. Unfortunately, Byzantine attackers can easily circumvent the existing defenses in non-independent identically distributed (non-IID) scenarios, stemming mostly from the high dimensionality of local models and the intricate non-linear relationships among local models. As a new robust FL framework, Basalt is designed to defend against Byzantine attacks while enhancing the performance of the global model in non-IID scenarios. Basalt builds an efficient detector that captures the non-linear relationships among high-dimensional models to support the accurate identification of malicious clients. Furthermore, it introduces a heuristic aggregation mechanism based on generalization capability, aiming at boosting global model performance. Our extensive experimental analysis shows Basalt's superior performance over existing defense methods. It achieves 100% accuracy in detecting malicious activity on the MNIST dataset. [Fig.1](#system) shows the framework of  Basalt.

<center>
    <img id= "system" style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="https://github.com/NSSLab-AI/Basalt/assets/53158153/5821a6bc-d3f7-4611-9f17-ab7bab466c54">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">Fig. 1 The entire  Basalt system can be divided into three models: (i) Approximation of information
stored in weights (ii) Byzantine attacker identification based on non-linear
relationships  (iii) Aggregation mechanism based
on generalization capability.</div>
</center>

# Requirements

> Run: pip install -t requirements.txt

# Run experimental evaluation

> Run: python main.py

# Citation

this paper has been submitted in ICDM
