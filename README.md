# HMM-TNOS-Estimation

### Thesis: The Estimation of Number of States in Hidden Markov Model

### Abstract
A hidden Markov model (HMM) is a statistical model widely used in the area of biology, finance, and speech recognition. It is necessary to determine the number of states before applying this model to the data. Gassiat and Rousseau (2014) have proposed a Bayesian sampling method from which the estimator is consistent when the sample size tends to infinity. However, the Markov chain Monte Carlo method used as a Bayesian sample method was time consuming and did not yield ideal results. Therefore, a practical improved method was proposed for estimating the number of states in hidden Markov models based on the concept in Gassiat and Rousseau (2014). The improved method could successfully estimate the number of states on both simulated data and single molecule Föster resonance energy transfer data. Finally, the improved method combined with a 2D-CNN model extends its application on HMMs with different parameter settings and gives suitable suggestions.

### File Description
There are five training weights files `model_1.h5` to `model_5.h5` obtained by training the five-fold 2D-CNN model.

![image](https://user-images.githubusercontent.com/35397383/126596803-1a877c35-1bed-40e9-a7d9-2fb7412899ba.png)

