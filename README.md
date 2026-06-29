# SportB Supply Chain Optimization Model

## Team Project
This project was completed as part of a team of four students.

### My Contribution
I contributed to:
- Developing the **Baseline optimization model (Q2)**.
- Developing the **Next-Day Delivery optimization model (Q3)**.
- Building and testing the Excel/OpenSolver optimization models.
- Contributing to the analysis and presentation of the results.

# SportB Supply Chain Optimization Model

This repository contains the optimization models developed for the SportB project.

## File Structure

Color code throughout the sheet:

- **Orange:** Input data
- **Grey:** Intermediate calculations
- **Blue:** Decision variables
- **Green:** Objective function
- **Red:** Additional analysis
  
Demand: This section contains the history and projections of demand expressed in units.

Details: Data segmented by State and by Region (West, Southwest, Northwest, Midwest, Northeast, Southeast).

Metrics: Annual forecasts (2024-2030), regional summaries, and shipment volume estimates (based on a unit/order ratio).

Parameters: Centralizes all input variables required for the model calculations.

General assumptions metrics

Warehouse Costs: Fixed costs (FC) and variable costs (VC) for small and large infrastructures, along with their respective capacities.

Logistics: Inbound and Outbound transportation cost matrices between sources, warehouses, and regions.

Sources: Capacities and costs associated with various supply points (Suzhou, Juarez, US sources).

2. Modeling Scenarios
Each sheet represents a specific simulation addressing a strategic issue:

• Q1_ST_Louis only: Impact study of a centralized network relying solely on St. Louis, including an analysis of lost revenue in the event of an inability to meet total demand.
• Q2_Model_Baseline: Base case configuration optimizing the optimal network to minimize total costs over the 2025-2027 period.
• Q3_next_day: Flow and cost modeling adapted to a next-day delivery constraint.
• Q4_Resilient: Optimization scenario prioritizing service continuity and network robustness against unforeseen disruptions, as well as a risk resilience analysis.
• Q5_Model_international: Integrates the complexities of international flows, supplier utilization, and global service rates.
• Q6_insourcing: Comparative analysis of the economic impact of insourcing relative to the baseline models.

Running the models:

To run the optimization models:
1. Open Excel with the office version (OpenSolver will not work with the online version).
2. Open OpenSolver and enable macros.
3. For each sheet with an optimization model : Click Solve and the optimal results will appear.
