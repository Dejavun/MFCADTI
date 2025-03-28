# MFCADTI
**MFCADTI: improving drug-target interaction prediction by integrating multiple feature through cross attention mechanism**
![Image text](https://github.com/Dejavun/MFCADTI/blob/086f9db38b17dc13066b7442fb782b81fe807a72/CrossAttentionDTI.png)
Fig. 1. The framework of MFCADTI.The MFCADTI framework consists of three modules: A. Network feature extraction. B. Attribute feature extraction. C. Cross-attention feature fusion and prediction.

# Dependencies
·pytorch==1.12.0
·numpy==1.23.1
·pandas==1.4.3
·tensorboardX==2.6
·tensorflow==2.6.0
·keras==2.9.0
·scikit-learn==1.1.1
·RDKit==2022.9.3
·gensim==4.2.0
·subword-nmt==0.3.8

# Dataset
In the dataset folder, we provide the processed data of Luo dataset.

# ESFP and dictionary
The ESFP folder contains the data needed for the FCS embedding method that is built based on MolTrans https://github.com/kexinhuang12345/MolTrans. The "dictionary" directory includes the dictionaries constructed for drug and target sequences in the luo dataset.

# Resources
·main.py: train and test the model
·hyperparameter.py: set the hyperparameter of MFCADTI
·model.py: MFCADTI model architecture
·measure.py: The module for calculating metrics

# Setting directory
Make the "result" directory before running the model. The run results are saved in the "result" directory

# Run
python main.py


