## Workflow

```
Sensitivity Analysis
        │
        ▼
Latin Hypercube Sampling (DOE)
        │
        ▼
ANSYS Fluent Simulations
        │
        ▼
Dataset Generation
        │
        ▼
Random Forest Benchmark
        │
        ▼
Gaussian Process Regression
        │
        ▼
5-Fold Cross Validation
        │
        ▼
External Validation
        │
        ▼
NSGA-II Multi-objective Optimization
        │
        ▼
Optimal Operating Conditions
```


## Repository Structure

```
├── Data/
│   ├── dataset.csv
│   ├── DOE.csv
│   ├── Testdata.csv
│   └── Testresults_ansys.csv
│
├── Models/
│   ├── gpr_h2.pkl
│   ├── gpr_eff.pkl
│   ├── gpr_vloss.pkl
│   └── gpr_deg.pkl
│
├── Results/
│   ├── Pareto.csv
│   ├── Optimal_Operating_Conditions.csv
│   ├── GPR_5Fold_CV.csv
│   ├── RF_5Fold_CV.csv
│   ├── External_Validation.csv
│   └── Model_Comparison.csv
│
├── Figures/
│
└── PEM_Electrolyzer.ipynb
```
