
# Summer Analytics 2025 | CAC, IIT Guwahati

A collection of coursework, hackathon submissions, and a capstone project completed as part of **Summer Analytics 2025**, organized by the **Consulting & Analytics Club (CAC), IIT Guwahati**.

This repository showcases practical applications of **Python, Data Analytics, Feature Engineering, Data Modeling, and Interactive Visualization**.

The primary highlight is a capstone project on **Dynamic Pricing for Urban Parking Lots**, exploring how parking prices can be adjusted based on real-time demand and competitive conditions.

---

## Repository Structure

```text
CAC-IIT-Summer-Analytics-2025/
│
├── Capstone Project/
│   └── Dynamic Pricing for Urban Parking Lots
│
├── SA2025_W1_CJ.ipynb
├── CAC_IIT_Wk2_Hackathon.ipynb
├── CAC_IIT_Wk4_Hackathon.ipynb
│
└── README.md
```

## Capstone Project: Dynamic Pricing for Urban Parking Lots

### Project Overview

Traditional parking systems often use fixed pricing, regardless of changing demand, traffic congestion, or parking availability.

This project explores a **dynamic pricing system for 14 urban parking lots**, using data-driven models to adjust prices based on demand-related factors.

The objective is to investigate how different pricing strategies respond to changing parking conditions.

### Pricing Models

Three pricing approaches were explored:

**1. Baseline Linear Pricing**
- Establishes a simple benchmark for dynamic price adjustments.
- Provides a reference for comparing more complex pricing strategies.

**2. Demand-Based Pricing**
- Estimates parking demand using multiple input features.
- Adjusts prices according to changes in demand conditions.
- Considers occupancy, queue length, traffic density, and location-related factors.

**3. Competitive Pricing**
- Incorporates the influence of nearby parking lots.
- Considers location proximity and competitive pricing conditions.
- Explores how neighboring parking availability may affect pricing decisions.

### Key Features

- **Data Preprocessing:** Cleaning and transforming parking-related datasets using Python and pandas.
- **Feature Engineering:** Extracting demand indicators such as occupancy rate, queue length, traffic density, and location proximity.
- **Pricing Model Development:** Implementing baseline, demand-based, and competitive pricing strategies.
- **Streaming Data Processing:** Using Pathway to process changing parking data.
- **Interactive Visualization:** Creating dynamic pricing visualizations using Bokeh.
- **Model Comparison:** Examining how different pricing approaches respond to changes in parking demand.

### Tech Stack

| Technology | Application |
|------------|-------------|
| Python | Core programming and pricing logic |
| pandas | Data preprocessing and manipulation |
| NumPy | Numerical computations |
| Pathway | Streaming data processing |
| Bokeh | Interactive data visualization |
| Jupyter Notebook | Development and experimentation |

### Project Workflow

```text
Parking Lot Dataset
        |
        v
Data Preprocessing
        |
        v
Feature Engineering
        |
        v
Pricing Model Development
        |
        +---- Baseline Linear Pricing
        |
        +---- Demand-Based Pricing
        |
        +---- Competitive Pricing
        |
        v
Dynamic Price Calculations
        |
        v
Interactive Visualization (Bokeh)
```

---

## Weekly Assignments & Hackathons

The repository also contains Jupyter notebooks completed throughout the Summer Analytics 2025 program.

| Notebook | Description |
|----------|-------------|
| [Week 1](SA2025_W1_CJ.ipynb) | Week 1 coursework and exercises |
| [Week 2 Hackathon](CAC_IIT_Wk2_Hackathon.ipynb) | Week 2 analytics hackathon submission |
| [Week 4 Hackathon](CAC_IIT_Wk4_Hackathon.ipynb) | Week 4 analytics hackathon submission |
| [Capstone Project](Capstone%20Project/) | Dynamic Pricing for Urban Parking Lots |

These notebooks document hands-on practice and application of data analytics concepts throughout the program.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/chaaitra001/CAC-IIT-Summer-Analytics-2025.git
cd CAC-IIT-Summer-Analytics-2025
```

### 2. Set Up Your Environment

Ensure that Python and Jupyter Notebook or JupyterLab are installed.

Install the main libraries used in the capstone:

```bash
pip install pandas numpy pathway bokeh jupyter
```

Additional dependencies may be required depending on the individual notebook.

### 3. Run the Notebooks

Open the repository using Jupyter Notebook, JupyterLab, or Google Colab.

For the capstone project, navigate to the `Capstone Project` directory and open the relevant notebook.

Ensure that the dataset paths are configured correctly before execution.

---

## Skills Demonstrated

- **Data Analytics:** Data preprocessing, exploratory analysis, and feature engineering.
- **Data Modeling:** Developing pricing models using demand-related variables.
- **Python Programming:** Building data-processing and numerical computation workflows.
- **Streaming Data Processing:** Working with Pathway for dynamic data pipelines.
- **Data Visualization:** Developing interactive visualizations using Bokeh.
- **Analytical Problem-Solving:** Translating real-world parking demand factors into pricing strategies.

---
