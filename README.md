# Monte-Carlo-Simulation-Supply-Chain-Management

This project showcases a Monte Carlo simulation to model uncertainty in supply chain management. Using Python, the simulation explores the impact of product demand variability, transportation delays, and supply disruptions on inventory levels for a 252-business-day period, with 200 iterations to assess outcomes.

## Key Points

- **The Problem:** 
  - **Company A** deals with fluctuating product demand, transportation delays, and supply disruptions. The goal is to determine optimal inventory levels and reduce risks from supply chain volatility.
  
- **Simulation Approach:**
  - The Monte Carlo simulation accounts for daily demand, unit price growth, lead time variance, and reorder levels. Reorders are triggered based on stock levels and lead times.
  - The simulation generates results such as average stockouts and total order costs to help make data-driven inventory management decisions.

- **Results & Observations:**
  - A histogram of stockout frequency across products illustrates inventory stability.
  - Most products show low stockouts, indicating efficient inventory control, while some outliers suggest specific issues.
  
- **Suggested Improvements:**
  - Reduce safety stock for low-stockout products to free up capital.
  - Investigate high-stockout products to identify areas for demand forecasting and supplier performance improvement.
  - Optimize procurement and logistics to lower overall order costs.

## Skills & Concepts
- Python programming for data processing and Monte Carlo simulation
- Supply chain management and inventory optimisation
- Data analysis and statistical modeling

This project provides a blueprint for optimising inventory and reducing operational risks in a supply chain. The detailed Python code implements the Monte Carlo simulation and supports further investigation and refinement.
