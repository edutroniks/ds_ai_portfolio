# Half‑Marathon Predictor App

This project delivers a practical machine learning application that predicts half‑marathon finish times based on a runner’s training history and personal characteristics. It demonstrates a complete, reproducible workflow: data preparation, model training, evaluation, and deployment as an interactive web app.

## Contents

- [GitHub repository](https://github.com/edutroniks/hmpredictor)
- [App link](https://hmpredictor-dvfxw.ondigitalocean.app/)

## Project Overview

The goal of this project is to build a reliable and user‑friendly tool that helps runners estimate their expected half‑marathon performance. The app is designed for both hobby runners and coaches who want quick, data‑driven predictions.

The workflow includes:

- structured data preprocessing  
- feature engineering based on training metrics  
- model selection and evaluation  
- error analysis and bias checks  
- deployment as a Streamlit application  

## How the Model Works

The model predicts finish time using features such as:

- recent training volume  
- pace distribution  
- long‑run performance  
- personal characteristics  

The final model was selected based on performance, stability, and interpretability. The training pipeline is fully reproducible and separated from the app code.

## The App

The Streamlit app allows users to:

- input their training data  
- adjust key parameters  
- receive an estimated finish time  
- view model confidence and interpretation  

The interface is clean, minimalistic, and optimized for clarity.

## Why This Project Matters

This project shows how machine learning can be turned into a practical tool that supports real‑world decision‑making. It highlights your focus on:

- reproducible ML  
- user‑oriented design  
- clear insights  
- reliable deployment  


## Architecture

The HM Predictor App follows a clean, reproducible structure that separates
data preparation, model training, and application logic.

User Input
    ↓
Streamlit App (UI Layer)
    ↓
Feature Processing
    ↓
Trained ML Model (loaded from artifacts)
    ↓
Prediction Engine
    ↓
Result Display (finish time + interpretation)


