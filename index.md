## Selected Data Science projects

---

### Automated speech Keyword Spotting with 1D and 2D CNNs

This was a fun deep learning audio project which classified one second of audio into one of 11 different categories! 

Two different model setups were explored - feeding one second raw waveforms to a 1-Dimensional ConvNet, vs. transforming raw waveform to a frequency representation and extracting 2D features by using Mel-Frequency Capstrum Coefficients (MFCC), which were then fed into a 2D ConvNet. 

The best 1D ConvNet obtained 81.25% Validation accuracy, while the 2D ConvNet peaked at 92.52% validation accuracy!

<img src="images/mfcc-1024x235.png?raw=true" />

[![](https://img.shields.io/badge/Python-grey?style=for-the-badge&logo=Python)](#) ![](https://img.shields.io/badge/AWS-%23FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white) [![](https://img.shields.io/badge/Tensorflow-blue?style=for-the-badge&logo=tensorflow)](#) [![](https://img.shields.io/badge/numpy-black?style=for-the-badge&logo=numpy)](#) 

---

### Weakly Supervised Machine Learning Research

In this research project, I worked with OpenStax researchers to explore Weakly Supervised machine learning. We showed that it is possible to achieve similar results to fully supervised learning (having ground truth labels) versus models trained on Snorkel-labeled data for predicting Bloom's taxonomy. This labeled data was created using expert domain knowledge. 

Natural language processing techniques were used to create features for various SciKit-Learn models. Then, we compared results from each of the models, and demonstrated that Weakly Supervised models had similar accuracy, with no ground truth labels!

<img src="images/weak_supervision.jpeg?raw=true" />

[![](https://img.shields.io/badge/Python-grey?style=for-the-badge&logo=Python)](#) ![](https://img.shields.io/badge/AWS-%23FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white) [![](https://img.shields.io/badge/SKlearn-blue?style=for-the-badge&logo=Scikit-learn)](#) [![](https://img.shields.io/badge/NLP-black?style=for-the-badge)](#) 

---

### Inventory tracker

Using Python, AWS, and RShiny, I developed a neat interactive app to track inventory for a small business. 

First, I utilized a Python script to extract data from the business’s website through Shopify REST APIs and clean the data. I used cron jobs to automate this and update daily, storing the data in AWS. Then, I accessed the cloud database from R and built an interactive tracking website using RShiny.

<img src="images/mobility.png?raw=true" />

[![](https://img.shields.io/badge/Python-grey?style=for-the-badge&logo=Python)](#) ![](https://img.shields.io/badge/AWS-%23FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white) [![](https://img.shields.io/badge/R-blue?style=for-the-badge&logo=R)](#) [![](https://img.shields.io/badge/RShiny-black?style=for-the-badge&logo=RShiny)](#)

---

### Bayesian Model Selection for Ising Graphical Models

Exploring applications of Bayesian inference to the Ising model. Extends the Decoupling Shrinkage and Selection Loss (Hahn and Carvalho, 2015) to Ising models. In order to calculate the DSS Loss, the psuedolikelihood is used to address the intractability of likelihood calculations with the Ising normalizing constant.

<img src="images/bayesian_ising.png?raw=true" />

[![](https://img.shields.io/badge/R-blue?style=for-the-badge&logo=R)](#) [![](https://img.shields.io/badge/Jupyter-white?style=for-the-badge&logo=Jupyter)](#)

---

### Using Econometrics to learn about Political Funding

In this project, I used matching theory to explore the market for political funding in the US.

Then, we describe a variety of features used to describe political candidates and contributors. These features are used to simulate production in matches (for more information on the matching framework see Koopmans and Beckmann (1957))

To simulate the market, parameters were estimated using code in Julia. The approach used for parameter estimation is the semiparametric maximum score estimator, following JT Fox (2007).

[![](https://img.shields.io/badge/Julia-green?style=for-the-badge&logo=Julia)](#) [![](https://img.shields.io/badge/Python-grey?style=for-the-badge&logo=Python)](#)
![](https://img.shields.io/badge/AWS-%23FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
---

