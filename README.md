# Proj_11B_Neural_Network_California_Dataset

## Introduction  
This project implements a simple neural network model applied to the California Housing Dataset. The dataset contains statistics about houses in various California districts. The main objective is to predict the median house value based on these features.

## Purpose  
- To analyze the California Housing Dataset  
- To forecast house prices using a neural network  
- To measure model performance using MSE and R2 score

## Main Features  
 **Data Processing:**  
   - Scaling (StandardScaler)  
   - Train-test split  
 **Modeling:**  
   - Keras Sequential model  
   - Simple architecture with Dense layers  
   - 'relu' activation and 'adam' optimizer  
 **Evaluation:**  
   - Mean Squared Error (MSE)  
   - R2 score  
 **Visualization:**  
   - Plot of training loss (MSE)

## How to Use

 **Install required libraries:**
   ```
   pip install scikit-learn keras matplotlib
   ```

 **Run the code:**  
   - Execute the `Proj_11B_Neural_Network_California_Dataset.py` file.  
   - The script will download and process the dataset, build the model, train it, and display the results.

 **View the results:**  
   - Output will show Test MSE and R2 score.  
   - A graph of training loss will also be shown.

## Dataset Features

| Feature      | Description              |
|--------------|-------------------------|
| MedInc       | Median income           |
| HouseAge     | Age of the house        |
| AveRooms     | Average rooms           |
| AveBedrms    | Average bedrooms        |
| Population   | Population              |
| AveOccup     | Average occupancy       |
| Latitude     | Latitude                |
| Longitude    | Longitude               |

**Target:**  
- MedHouseVal: Median house value
