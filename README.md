# 💧 AI-Powered Water Potability Analyzer

This is an end-to-end machine learning project that tackles a critical question: **Is this water safe to drink?**

This repository contains a complete, deployed web application that uses a trained AI model to predict water quality. It's built to transform complex chemical data into a simple, actionable answer: **Safe** or **Unsafe**.

**[You can see the live application here!](https://shivamsingh96-deployement-of-automatic-water-qualit-main-8ftkls.streamlit.app/)**

![Application Preview](water-testing.jpg)

## 🎯 The Core Mission

The goal of this system is to provide an accessible, intelligent tool for assessing water quality. It functions as a "digital litmus test" for potability. By analyzing a set of key indicators, the application can flag potentially hazardous water sources that might otherwise seem safe.

## 🧠 The AI "Brain"

The heart of this application is a robust **Machine Learning Classifier**.

This model (`Water_Quality_Prediction_System.pkl`) was trained on a dataset of water samples, learning the intricate relationships between various chemical and biological components. It makes its predictions by analyzing:

* Aluminium
* Ammonia
* Fluoride
* Chromium
* Copper
* Bacteria

This trained "brain" is the engine that powers every prediction, encapsulating all the statistical knowledge from the research phase.

## 🖥️ The Interactive Experience

The AI model is brought to life through a user-friendly web application, built entirely in Python using the **Streamlit** framework (`main.py`).

This interface provides a simple, clean dashboard where a user can input the values for each parameter. On submission, the app feeds this data to the model in real-time and immediately displays the final classification, bridging the gap between a complex data science model and a usable, practical tool.

## 🔬 The Research

All foundational work is documented in the `Water_Quality_Prediction_with_Python.ipynb` Jupyter Notebook. This file shows the complete journey:

* **Data Cleaning:** Handling missing or erroneous data.
* **Exploratory Data Analysis (EDA):** Discovering patterns and correlations.
* **Model Selection:** Comparing different algorithms to find the most accurate classifier.
* **Final Training:** Building and saving the final model that is used in the app.

This project demonstrates the full lifecycle of a data science product, from initial research in a notebook to a live, interactive, and deployed web application.