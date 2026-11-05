# Smart EV Charging Scheduling and Energy Cost Optimization Using Differential Evolution

## 1. Project Overview

This project implements Differential Evolution (DE), an evolutionary optimization algorithm, to optimize electric vehicle (EV) charging schedules and reduce electricity costs.

The system simulates a charging station with 20 electric vehicles, considering battery requirements, vehicle availability, charger power limits, station capacity, and time-varying electricity prices.

## 2. Problem Statement

Uncoordinated EV charging can increase electricity expenses and create high peak demand.

The objective is to develop an optimization approach that schedules EV charging during suitable time periods while satisfying vehicle charging requirements and station constraints.

## 3. Algorithm Used

**Differential Evolution (DE)**

The algorithm uses four main operations:

* Population Initialization
* Mutation
* Crossover
* Selection

A feasibility-preserving schedule decoder converts charging priorities into schedules that satisfy the charging constraints.

## 4. Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Google Colab
* Differential Evolution

## 5. Experimental Configuration

| Parameter        |    Value |
| ---------------- | -------: |
| Number of EVs    |       20 |
| Time Slots       | 24 hours |
| Population Size  |       40 |
| Generations      |      100 |
| Mutation Factor  |      0.8 |
| Crossover Rate   |      0.9 |
| Charger Power    |     7 kW |
| Station Capacity |    50 kW |
| Independent Runs |       10 |

## 6. Experimental Results

| Metric                  |    Result |
| ----------------------- | --------: |
| Baseline Charging Cost  | ₹3,844.61 |
| Optimized Charging Cost | ₹3,802.32 |
| Cost Savings            |    ₹42.29 |
| Cost Reduction          |      1.1% |
| Charging Completion     |      100% |
| Fully Charged Vehicles  |     20/20 |
| Maximum Station Load    |     50 kW |

All charging constraints were satisfied in the reported optimized schedule.

## 7. Visualizations

The project generates eight visualizations:

1. Electricity Price Distribution
2. Baseline EV Charging Schedule
3. Optimized EV Charging Schedule
4. EV Charging Load Distribution
5. Charging Cost Comparison
6. Differential Evolution Convergence Curve
7. EV Charging Completion Analysis
8. Statistical Performance Analysis

## 8. How to Run

1. Download the Jupyter Notebook from this repository.
2. Open Google Colab.
3. Upload the notebook.
4. Run the cells sequentially.
5. View the experimental results and generated graphs.

## 9. Project Scope

This project uses simulated EV charging data and illustrative electricity prices. It demonstrates how evolutionary optimization can support intelligent energy management.

## 10. Conclusion

Differential Evolution was implemented to optimize EV charging priorities under operational constraints.

The experimental results demonstrate a reduction in charging cost while achieving 100% charging completion and respecting the charging station's capacity.

The project illustrates the application of Evolutionary Computing to smart energy management.
