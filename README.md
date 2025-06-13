# Transformer for Time Series Anomaly Detection

![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)
![Made With Python](https://img.shields.io/badge/Made%20with-Python%20%2B%20JS-yellow.svg)
![Node.js](https://img.shields.io/badge/Backend-Node.js-brightgreen.svg)
![React](https://img.shields.io/badge/Frontend-React-blue.svg)
![Status](https://img.shields.io/badge/status-Active-success.svg)

This project presents a Transformer-based approach to detect anomalies in time-series data, particularly applied to financial data (Bitcoin price data from 2018–2024). By leveraging the powerful self-attention mechanisms of the Transformer architecture, the model identifies point, contextual, and collective anomalies with high accuracy.

---

## 📖 Overview

Anomalies in time series data — such as sudden spikes or drops — can indicate critical events like fraud, system failure, or health deterioration. Our model uses Transformer architecture, enhanced by:

- *Anomaly Attention Mechanism*
- *Association Discrepancy*
- *Minimax Strategy*
- *Reconstruction Loss*

The solution is suitable for both *univariate* and *multivariate* time series anomaly detection.

---

## 🏗 Architecture

- *Frontend*: React.js
- *Backend*: Express.js (Node.js)
- *Model*: Transformer (implemented with and without PyTorch)
- *Visualization*: Matplotlib (Python) and Chart.js (React)
- *Dataset*: Bitcoin Historical Prices (2018–2024)

---

## 🔧 Technology Stack

| Area             | Tech Used           |
|------------------|---------------------|
| Programming      | Python, JavaScript  |
| Libraries        | NumPy, Pandas, PyTorch, Matplotlib, Chart.js |
| Frontend         | React.js            |
| Backend          | Express.js          |
| ML Components    | Transformer, Attention, Backpropagation |
| Storage          | CSV, JSON           |

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally:

### 🔧 Prerequisites

Make sure the following are installed on your system:

- [Node.js](https://nodejs.org/) (v18 or above)
- [npm](https://www.npmjs.com/)
- [Python](https://www.python.org/) (if using the ML model backend)

### 📦 Step 1: Install Dependencies
      Step-2: Run the backend server: node backend.js
      Step-3: Run the front end server: npm start
              The app will automatically open in your default browser at http://localhost:3000.

📊 Results
Accuracy (Basic Transformer): 87.25%
Accuracy (PyTorch): 82.06%
Detected Anomalies: Point anomalies, contextual spikes
UI Features: CSV upload,Dynamic visualization,Click to highlight anomaly index

📚 References
Anomaly Transformer (ICLR 2022)
Attention is All You Need (Vaswani et al., 2017)
Dataset: Historical Bitcoin prices from Yahoo Finance and Binance API

Submitted by:
Kalwa Sai Sreeja
Under the guidance of Mr. K. Ramakrishna

📄 License
This project is licensed under the MIT License. See LICENSE for more information.
