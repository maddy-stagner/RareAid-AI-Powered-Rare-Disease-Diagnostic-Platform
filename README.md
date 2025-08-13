# RareAid-AI-Powered-Rare-Disease-Diagnostic-Platform

RareAid is an innovative AI-driven platform designed for the early detection and diagnosis of rare diseases. This project simulates a healthcare diagnostic tool using synthetic data generation, machine learning (via TensorFlow/Keras for disease prediction based on symptoms and genetic markers), and an interactive user interface built with Gradio. The system generates synthetic patient data for rare diseases, trains a neural network model to predict diseases from symptoms and genes, and includes a chatbot interface for symptom-based questioning.
Key features:

Synthetic Data Generation: Creates a dataset of 500 simulated patients with symptoms, genes, and associated rare diseases.
Machine Learning Model: A simple feedforward neural network that predicts rare diseases (e.g., Gaucher disease, Cystic fibrosis) based on encoded symptoms and genes.
Interactive Chatbot: A Gradio-based web app that asks users yes/no questions about symptoms, tracks analytics (e.g., session counts, yes/no responses), and provides a professional UI with navigation (Home, About, Features, Contact, Chatbot, Analytics).
Analytics Dashboard: Tracks user interactions for insights into symptom responses.
Professional Styling: Custom CSS for a modern, healthcare-themed interface.

This project is ideal for educational purposes, prototyping AI in healthcare, or as a starting point for real-world rare disease diagnostics. Note: This uses synthetic data and is not intended for actual medical use. In a production scenario, integrate real datasets and ensure compliance with regulations like HIPAA.
The project is built in Python using libraries like Pandas, NumPy, Scikit-learn, TensorFlow/Keras, and Gradio. It was developed in a Jupyter Notebook environment (e.g., Google Colab).

