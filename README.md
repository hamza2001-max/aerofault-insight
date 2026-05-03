# AeroFault Insight

AeroFault Insight is a data-driven aircraft fault analysis project focused on detecting abnormal behavior and predicting possible pre-fault patterns from flight data.

The project uses healthy aircraft data as a reference, applies anomaly detection methods, and builds prediction models to identify files or rows that may indicate early signs of faults.

## Key Features

- Rebuilds aircraft datasets from raw Excel files
- Separates healthy and defective flight data
- Applies healthy-reference anomaly detection
- Uses scaling, PCA reconstruction error, Isolation Forest, and Mahalanobis-style scoring
- Selects anomaly thresholds using file-level validation
- Creates time-based features for fault prediction
- Trains and compares machine learning models
- Reports row-level and file-level performance
- Generates plots, metrics, and reliability notes

## Project Files

```text
.
├── 01_consolidated_anomaly_detection.ipynb
├── 02_consolidated_fault_prediction_and_report.ipynb
├── aero_fault_analysis_enhanced_report.pdf
├── data/
├── outputs/
└── README.md
```

## Requirements

The project is built using Python and common data science libraries.

```text
python
pandas
numpy
scikit-learn
matplotlib
seaborn
openpyxl
```

Install the required packages using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl
```

## How to Run

1. Place the raw Excel flight data files in the data folder.

2. Run the anomaly detection notebook:

```text
01_consolidated_anomaly_detection.ipynb
```

3. Run the fault prediction and report generation notebook:

```text
02_consolidated_fault_prediction_and_report.ipynb
```

4. Review the generated metrics, plots, and final report.

## Output

The project generates:

- Anomaly scores
- File-level anomaly rates
- Fault prediction metrics
- Model comparison results
- Confusion matrix
- ROC and precision-recall curves
- Prediction timelines
- PDF report

## Author

Hamza Ali
