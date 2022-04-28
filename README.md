# CIS522-DL-Tribiotics

**Team Members**:<br/>
Trevor Chan, Jordan Matelsky, Jiazhen Rong <br/>

This repository contains our code for Upenn 2022 SPRING CIS 522 final project.<br/>
In this project, we classied public COVID-19 X-ray image dataset with ResNet and applied interpretable methods GRAD-CAM and SHAP to interpret the model and result.

**Standard Training pipeline**: <br/>
Including Data preprocessing & Transfer Learning of ResNet:  <br/>
https://colab.research.google.com/drive/1gm7ZMR2nmQxS42vv4Osw4D6XJQWHbOZv?usp=sharing <br/>
(Anti masking training) - https://colab.research.google.com/drive/1SD2bzAuRItR6w8HCZgx4lprsx8KspsRr <br/>

**Baseline visualization & GRAD-CAM pipeline**: <br/>
Including Baseline CNN filters visualization & GRAD-CAM method:<br/>
https://colab.research.google.com/drive/1_7ubTDYWu7CzmX98T-S7cEpqbeaUjI7L?usp=sharing<br/>

**SHAP pipeline & results**:<br/>
https://colab.research.google.com/drive/1gA9Ti6JHqzEFF_uBe-ryWkiHOAlFc71a?usp=sharing <br/>

**Machine Learning pipeline**:<br/>
including logistic regression & random forest:<br/>
ML_Baseline.ipynb & Dataset_Exploration.ipynb within this github. <br/>

**saved_models**: <br/>
This folder contains trained ResNet weights for full X-ray image, keeping the lungs and masking out the lungs.
