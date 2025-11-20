https://cis-300-honors-contract-6eb8crsy6xyatyxuyzaiwf.streamlit.app/

## About This Project

For my **CIS 300 Honors Contract**, I integrated concepts from **machine learning** and **web development** to create an interactive, web-based credit default prediction app. The goal was to design a tool that allows non-technical users to interact with a predictive model in a simple and intuitive way—bridging the gap between technical data science and practical business decision-making.

## Project Overview

I built a **classification model** that predicts the likelihood of a customer defaulting on a loan, based on attributes such as employment, credit history, and financial standing. The model was designed in the context of a mock German credit firm seeking to identify high- and low-risk clients to improve retention and acquisition strategies.

The web interface, developed with **Streamlit**, enables users to input customer data through sliders and dropdown menus. Upon submission, the app processes these inputs through the trained model and outputs a probability of default.

## Technical Implementation

1. **Data Preparation** – Cleaned and encoded historical loan data for model training.
2. **Model Building** – Trained a supervised classification model using Python’s machine learning libraries and evaluated it on unseen data to measure accuracy.
3. **Packaging** – Saved and reloaded the finalized model for deployment.
4. **Interface Development** – Built an interactive frontend using Streamlit, including sliders and dropdowns for user input.
5. **Deployment** – Deployed the completed app to **Streamlit Cloud** for live interaction.

## Business Use Case

The application simulates how analysts at a credit firm could predict default risk using client data. By combining probability outputs with demographic and behavioral features, analysts can:

* Identify risk patterns in client portfolios.
* Perform cluster analysis on defaulting vs. non-defaulting clients.
* Target new customers with low-risk profiles.

## Tools and Technologies

* **Python**
* **pandas**, **scikit-learn**, **Streamlit**
* **DataFrame manipulation**, **control flow logic** for data translation
* **Streamlit Cloud** for deployment

## Purpose

This project represents my effort to connect **data science** and **user experience design**. By creating an accessible interface for a machine learning model, I learned how to translate technical models into real-world, decision-driven tools—an essential skill for business analytics and applied AI work.
