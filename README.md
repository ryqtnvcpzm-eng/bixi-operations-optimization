# Optimizing BIXI Bike Allocation and Re-distribution

## Objective
This project leverages linear optimization to improve bike allocation and rebalancing operations for BIXI, Montreal's native bike-sharing system. The goal is to minimize bike shortages and optimize truck fleet routing to handle demand fluctuations across the city.

## Project Structure
* **`BIXI_Group_project_code.ipynb`**: Python code utilizing Gurobi for the two-phase linear optimization model.
* **`DA Project Report_AK.pdf`**: The comprehensive business report detailing the methodology, geographic clustering, and strategic recommendations.

## Methodology
* **Phase 1 (Baseline Allocation):** Grouped stations into geographic clusters and created a linear optimization model to distribute bikes efficiently based on peak outbound trip demand.
* **Phase 2 (Route Optimization):** Modeled the most efficient daily rebalancing routes for the BIXI truck fleet to prevent dock shortages and lost trips.

## Tools Used
Python, Gurobi (Linear Optimization), Pandas, Data Analytics
