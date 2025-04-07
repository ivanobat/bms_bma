# Bayesian model selection and averaging
Bayesian Model Selection (BMS) is typically more conservative than LASSO in terms of model selection, it results in more coefficients very close to 0. As a result, Bayesian Model Averaging (BMA) that relies on BMS weights may predict worse than LASSO. On the other hand LASSO is often worse at detecting the variables that truly matter (i.e. for explanatory purposes) than BMS. In this homework you will apply Bayesian Model Selection and Bayesian Model Averaging to the Vessel dataset and compare your results to those obtained with LASSO in Seminar 1. Recall that for this dataset our objective is to predict the content of compound 1 (sodium oxide) from the 1920 frequencies.

1. Load the Vessel data
2. Conduct a prior eliciation to choose $g$
3. Run a Bayesian model selection
4. Obtain predictions by Bayesian Model Averaging
5. Compare to the results obtained with LASSO

![image](https://github.com/user-attachments/assets/5ecb91b0-35bf-461f-82c4-8b8c8a68a856)

![image](https://github.com/user-attachments/assets/b64eadc9-b06f-4531-b91e-b6f23fa866b9)
