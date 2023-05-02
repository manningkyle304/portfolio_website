## Selected Data Science projects

---

### Automated speech Keyword Spotting with 1D and 2D CNNs

This was a fun little audio project which classified one second of audio into one of 11 different categories! 

Two different model setups were explored - feeding one second raw waveforms to a 1-Dimensional ConvNet, vs. transforming raw waveform to a frequency representation and extracting 2D features by using Mel-Frequency Capstrum Coefficients (MFCC), which were then fed into a 2D ConvNet. 

The best 1D ConvNet obtained 81.25% Validation accuracy, while the 2D ConvNet peaked at 92.52% validation accuracy!

<img src="images/mfcc-1024x235.png?raw=true" />

[![](https://img.shields.io/badge/Python-red?logo=Python)](#) [![](https://img.shields.io/badge/Cloud-black?logo=AWS)](#) [![](https://img.shields.io/badge/Tensorflow-red?logo=tensorflow)](#) [![](https://img.shields.io/badge/numpy-black?logo=numpy)](#) 

---

### Bla Bla

asdfasdf


---

### Inventory tracker

Using Python, AWS, and RShiny, I developed a neat interactive app to track inventory for a small business. 

First, I utilized a Python script to extract data from the business’s website through Shopify REST APIs and clean the data. I used cron jobs to automate this and update daily, using a cloud database to store the data. Then, I accessed the database from R and built an interactive tracking website using RShiny.

<img src="images/mobility.png?raw=true" />

[![Python](https://img.shields.io/badge/Python-red?logo=Python)](#) ![](https://img.shields.io/badge/AWS-%23FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white) [![R](https://img.shields.io/badge/R-red?logo=R)](#) [![](https://img.shields.io/badge/RShiny-black?logo=RShiny)](#)

---

### Bayesian Model Selection for Ising Graphical Models

Exploring applications of Bayesian inference to the Ising model. Extends the Decoupling Shrinkage and Selection Loss (Hahn and Carvalho, 2015) to Ising models. In order to calculate the DSS Loss, the psuedolikelihood is used to address the intractability of likelihood calculations with the Ising normalizing constant.

<img src="images/bayesian_ising.png?raw=true" />

[![](https://img.shields.io/badge/R-red?logo=R)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#) [![](https://img.shields.io/badge/Twitter-white?logo=Twitter)](#) [![](https://img.shields.io/badge/HuggingFace_Transformers-white?logo=huggingface)](#)

---

<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
