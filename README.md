# 🏦 Bank Teller Discrete-Event Simulation

> A discrete-event simulation project for analyzing customer queues, teller utilization, waiting times, and service performance in a bank environment.

## 📌 Overview

This project models a bank teller system using discrete-event simulation.

The simulation analyzes different staffing configurations and compares system performance when the bank operates with one, two, three, and four tellers.

The project focuses on customer arrivals, service times, queue behavior, waiting times, and teller performance.

## 🎯 Project Objectives

- Simulate customer arrivals and service processes.
- Model bank queues using discrete-event simulation.
- Compare different numbers of bank tellers.
- Analyze customer waiting times.
- Examine queue behavior and teller utilization.
- Evaluate the effect of additional tellers on system performance.

## 🔬 Simulation Versions

### 1. One Teller

Simulation of the bank operating with a single teller.

**File:**

```text
notebooks/one-teller-simulation.ipynb
```
### 2. Two Tellers
Simulation of the bank operating with two tellers.
**File:**
```text
notebooks/two-teller-simulation.ipynb
```
### 3. Three Tellers
Simulation of the bank operating with three tellers.
**File:**
```text
notebooks/three-teller-simulation.ipynb
```
### 4. Four Tellers
Simulation of the bank operating with four tellers.
**File:**
```text
notebooks/four-teller-simulation.ipynb
```
**📊 Input Data**
```text
The simulation uses customer arrival data provided in:
input/customer-arrival-data.txt
```
**📁 Repository Structure**
```text
Bank-Teller-Discrete-Event-Simulation/
│
├── README.md
│
├── documentation/
│   └── bank-teller-simulation-report.pdf
│
├── input/
│   └── customer-arrival-data.txt
│
└── notebooks/
    ├── one-teller-simulation.ipynb
    ├── two-teller-simulation.ipynb
    ├── three-teller-simulation.ipynb
    └── four-teller-simulation.ipynb
```
### 🛠️ Technologies

- Python
- Jupyter Notebook
- Discrete-Event Simulation
- Queueing Analysis
### 📈 Performance Analysis

The different teller configurations can be used to examine:
- Customer waiting times
- Queue behavior
- Teller utilization
- Service performance
- Effect of increasing teller capacity
### ▶️ How to Run

1. Install Python and Jupyter Notebook.
2. Clone this repository.
3. Open the project directory in Jupyter Notebook or JupyterLab.
4. Open any notebook from the notebooks/ directory.
5. Make sure the input file remains in the input/ directory.
6. Run the notebook cells sequentially.
```text
No database, API key, password, or external service is required for the included simulation notebooks.
```
### 📄 Documentation

The detailed project report is available at:
documentation/bank-teller-simulation-report.pdf

### 🚀 Project Structure

The project provides four simulation scenarios, allowing the bank's queue and service performance to be examined under different teller capacities.
1 Teller → 2 Tellers → 3 Tellers → 4 Tellers
This progression provides a basis for comparing how additional tellers affect customer service and queue performance.

**📚 Project Documentation**
```text
For additional details about the simulation methodology, implementation, and analysis, refer to the project report included in the documentation/ directory.
```
**📜 License**
```text
This project is intended for educational and portfolio purposes.
```

