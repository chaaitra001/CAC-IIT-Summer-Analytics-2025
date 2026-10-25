# Summer Analytics 2025 — CAC, IIT Guwahati

A collection of coursework, hackathon notebooks, and a capstone project completed as part of the **Summer Analytics 2025** program organized by the **Consulting & Analytics Club (CAC), IIT Guwahati**.

The repository documents practical work in Python-based data analysis, exploratory analytics, modeling, and visualization. The capstone focuses on **dynamic pricing for urban parking lots**, using demand-related features to explore how prices can respond to changing conditions.

## Repository contents

```text
CAC-IIT-Summer-Analytics-2025/
├── Capstone Project/             # Dynamic pricing capstone materials
├── SA2025_W1_CJ.ipynb            # Week 1 notebook
├── CAC_IIT_Wk2_Hackathon.ipynb   # Week 2 hackathon
└── CAC_IIT_Wk4_Hackathon.ipynb   # Week 4 hackathon
```

## Capstone: Dynamic Pricing for Urban Parking Lots

### Problem statement

Static parking fees may not reflect changes in occupancy, congestion, and nearby demand. This project explores **data-driven pricing approaches across 14 urban parking lots**, with the goal of adjusting prices in response to changing parking conditions.

### Approach

The capstone explores three pricing approaches:

1. **Baseline linear pricing:** establishes a straightforward benchmark for price adjustments.
2. **Demand-based pricing:** incorporates signals such as occupancy, queue length, traffic conditions, and location-related demand.
3. **Competitive pricing:** considers proximity to other parking lots when assessing price changes.

The workflow includes data preprocessing, feature engineering, pricing-model calculations, and interactive visualization of prices over time.

### Tools and technologies

| Tool | Use |
| --- | --- |
| Python | Data processing and pricing logic |
| pandas & NumPy | Data manipulation and numerical calculations |
| Pathway | Streaming data processing |
| Bokeh | Interactive price visualizations |
| Jupyter Notebook | Analysis, experimentation, and presentation |

### Key concepts

- Feature engineering using **occupancy rate, queue length, traffic density, and location proximity**
- Comparison of pricing strategies under changing demand conditions
- Processing data streams and visualizing dynamic model outputs
- Interpreting the relationship between demand indicators and parking prices

> **Note:** This is a modeling and analytics capstone, not a production parking-payment or reservation system. Numerical performance claims and live deployment details are intentionally omitted because they have not been independently verified from the notebook contents.

## Weekly notebooks

| Notebook | Description |
| --- | --- |
| [`SA2025_W1_CJ.ipynb`](SA2025_W1_CJ.ipynb) | Week 1 program work |
| [`CAC_IIT_Wk2_Hackathon.ipynb`](CAC_IIT_Wk2_Hackathon.ipynb) | Week 2 hackathon submission |
| [`CAC_IIT_Wk4_Hackathon.ipynb`](CAC_IIT_Wk4_Hackathon.ipynb) | Week 4 hackathon submission |
| [`Capstone Project/`](Capstone%20Project/) | Parking-lot dynamic pricing capstone |

## Getting started

1. Clone this repository:

   ```bash
   git clone https://github.com/chaaitra001/CAC-IIT-Summer-Analytics-2025.git
   cd CAC-IIT-Summer-Analytics-2025
   ```

2. Open the notebooks in **JupyterLab**, **Jupyter Notebook**, or **Google Colab**.
3. Install the packages required by the notebook you plan to run. For the capstone, relevant libraries include `pandas`, `numpy`, `pathway`, and `bokeh`.
4. Check the notebook's input-data paths and update them for your environment before running the cells in order.

The repository does not currently advertise a pinned dependency file, so package versions and input-data requirements should be checked against the notebooks.

## Skills demonstrated

**Data analytics:** data preparation, exploratory analysis, and feature engineering  
**Modeling:** translating real-world demand signals into rule-based pricing models  
**Data engineering:** Python pipelines and streaming-data concepts  
**Visualization:** interactive plots for communicating model behavior

## Author

**Guda Chaaitra Joseph**  
Computer Engineering | Second Major in Data Analytics  
Nanyang Technological University, Singapore

[GitHub Profile](https://github.com/chaaitra001)

---

*Developed as part of the CAC IIT Guwahati Summer Analytics 2025 program.*
