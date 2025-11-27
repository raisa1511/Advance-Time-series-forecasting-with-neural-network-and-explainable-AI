
# Project

Advance time series forecasting with neural network and explainable AI
A comprehensive implementation of multivariate time series forecasting using Long Short-Term Memory (LSTM) networks with integrated Explainable AI (XAI) techniques for model interpretability.

📋 Project Overview

This project demonstrates advanced time series forecasting by developing and rigorously evaluating sophisticated neural network models. The core focus extends beyond predictive accuracy to include model interpretability using Explainable AI techniques, making it suitable for deployment in sensitive business environments where understanding model decisions is crucial.

Key Features

· Multivariate Time Series Forecasting: Predict future values using multiple correlated features
· Deep Learning Models: Implementation of LSTM networks with proper architecture tuning
· Explainable AI Integration: SHAP values and feature importance analysis for model interpretability
· Statistical Baselines: Comparison against classical methods (SARIMAX, Moving Average)
· Production-Ready Code: Modular, tested, and well-documented implementation
· Comprehensive Evaluation: Multiple metrics (RMSE, MAE) and comparative analysis

Dataset

The project uses a synthetically generated multivariate time series dataset with:

· 5 correlated features: Energy consumption, temperature, humidity, wind speed, market price
· Complex seasonality: Multiple seasonal patterns (daily, weekly)
· Realistic patterns: Trends, noise, and missing values
· 5000+ timesteps: Hourly frequency data

Models Implemented

Deep Learning Models

· LSTM Network: Multi-layer LSTM with dropout regularization
· Temporal Convolutional Network (TCN): Alternative deep learning approach

Baseline Models

· SARIMAX: Seasonal AutoRegressive Integrated Moving Average with eXogenous variables
· Moving Average: Simple statistical baseline for comparison

🔍 Explainable AI Features

· SHAP Value Analysis: Global and local feature importance
· Permutation Importance: Alternative feature importance measurement
· Temporal Analysis: How feature importance evolves over time
· Business Interpretability: Actionable insights from model explanations