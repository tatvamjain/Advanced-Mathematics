# Learning Probability Density Function

## Dataset
- Feature: NO₂ concentration (x)  
- Link: https://www.kaggle.com/datasets/shrutibhargava94/india-air-quality-data  

## Step 1: Transformation
z = x + a_r * sin(b_r * x)

For roll number 102303480:
- a_r = 0.3  
- b_r = 0.3  

## Step 2: PDF Estimation
p̂(z) = c * exp(-λ * (z - μ)²)

Parameters estimated as:
- μ = mean(z)  
- λ = 1 / (2 * var(z))  
- c = √(λ / π)  

## Step 3: Output
- μ = 25.814687284943872  
- λ = 0.0014612298133120176
- c =0.021566731221112533

## Results
- Transformed data plotted  
- PDF approximated  

## Observations
- Transformation adds non-linearity  
- PDF follows data distribution
