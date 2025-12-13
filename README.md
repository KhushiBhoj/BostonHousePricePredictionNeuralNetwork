# Boston House Price Prediction using Neural Networks

This project predicts Boston housing prices using a **neural network regression model** built with TensorFlow/Keras.  

---

## **Project Overview**

- **Dataset:** Boston Housing dataset (506 samples, 13 features, target = PRICE).  
- **Goal:** Predict housing prices using a neural network.  

---

## **Features Used**

- `CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT`  

---

## **Approach**

- Preprocessing: Imputation + Standard Scaling.  
- Neural Network Architecture: `32 → 16 → 1` with ReLU activations.  
- Optimizer: Adam  
- Loss: Mean Squared Error (MSE)  
- Evaluation Metric: Mean Absolute Error (MAE)  
- Trained for 100 epochs with validation monitoring.  

---

## **Usage**

1. Clone repo:
```bash
git clone https://github.com/KhushiBhoj/BostonHousePricePredictionNeuralNetwork.git
cd BostonHousePricePredictionNeuralNetwork
