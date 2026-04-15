SYNTHETIC FLOOD SUSCEPTIBILITY MAPPING DATA
================================================================================

Generated: 2025-11-06 12:19:26

CONTENTS:
--------------------------------------------------------------------------------

1. synthetic_datasets/
   Contains all generated synthetic datasets in CSV format.
   Naming convention: synthetic_data_[METHOD]_[ROWS]rows.csv
   Example: synthetic_data_CTGAN_5000rows.csv

2. evaluation_plots/
   All visualization plots including:
   • Distribution comparisons
   • Correlation heatmaps
   • PCA projections
   • TSTR performance charts
   • Discriminator results
   • Performance ranking visualizations

3. evaluation_results/
   Quantitative evaluation metrics in CSV and JSON format:
   • complete_evaluation_summary.csv - All metrics for all configs
   • performance_based_ranking.csv - Final rankings
   • optimal_performance_details.json - Detailed breakdown

4. reports/
   Human-readable text reports:
   • ACADEMIC_EVALUATION_SUMMARY.txt - Executive summary
   • EVALUATION_REPORT.txt - Detailed analysis

5. metadata/
   Dataset information and configuration:
   • Cleaned_Data.csv - Original cleaned dataset
   • dataset_info.txt - Generation metadata

USAGE:
--------------------------------------------------------------------------------

To load a synthetic dataset:
   import pandas as pd
   data = pd.read_csv('synthetic_datasets/synthetic_data_CTGAN_5000rows.csv')

To view evaluation results:
   results = pd.read_csv('evaluation_results/complete_evaluation_summary.csv')

RECOMMENDED CONFIGURATION:
--------------------------------------------------------------------------------
Based on comprehensive evaluation (see performance_based_ranking.csv),
the optimal configuration will be listed in the ranking files.

CITATION:
--------------------------------------------------------------------------------
If you use this data, please cite:
[Your thesis citation will go here]

CONTACT:
--------------------------------------------------------------------------------
[Your contact information]
