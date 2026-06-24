# Mental Health Analyzer

*A Logistic Regression–Based Machine Learning Project*

## Overview

The **Mental Health Analyzer** is a machine learning project designed to predict whether an individual may require mental health support based on survey and behavioral data. Using a Logistic Regression model, the system classifies individuals into two categories:

* Requires Support
* Does Not Require Support

This project aims to promote awareness and provide early indications of mental health concerns. It is intended for educational purposes and is not a substitute for professional diagnosis or treatment.

## Features

* Mental health support prediction using machine learning
* Logistic Regression–based binary classification
* Data preprocessing and feature engineering
* REST API for real-time predictions
* Interactive web interface

## Tech Stack

* Python
* Scikit-Learn
* FastAPI
* Pandas
* NumPy

## Model Performance

* **Algorithm:** Logistic Regression
* **Test Accuracy:** 97%

## Installation

Clone the repository:

```bash
git clone https://github.com/ananyasgithubacc1/Mental-Health-Analyzer.git
cd Mental-Health-Analyzer
```

## Running the Backend Server

Navigate to the server directory:

```bash
cd server
```

Install dependencies:

```bash
npm install
```

Start the server:

```bash
npm start
```

or, for development:

```bash
npm run dev
```

## Running the Frontend Client

Open a new terminal and navigate to the client directory:

```bash
cd client
```

Install dependencies:

```bash
npm install
```

Start the client:

```bash
npm start
```

The application will typically be available at:

* **Frontend:** `http://localhost:3000`
* **Backend:** `http://localhost:5000`

## Project Structure

```text
mental-health-analyzer/
│
├── client/              # React frontend
├── server/              # Node.js backend
├── model/               # Trained Logistic Regression model
├── dataset/             # Dataset files
├── requirements.txt     # Python dependencies
└── README.md
```

## Disclaimer

This project is intended for educational and research purposes only. It should not be used as a replacement for professional medical advice, diagnosis, or treatment.
