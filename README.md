# Abid_Final_Project
# Hawaii Wildfire Vulnerability

This project reuses data and code from my thesis on wildfire vulnerability in
Hawaiʻi's Wildland–Urban Interface (WUI).

## Data
- `data/master_wildfire_dataset.csv` – WUI-level metrics exported from my thesis
  analysis. Each row is a WUI; columns include risk score,NDVI, slope,
  ignition density, and island/community identifiers.


## Outputs
Rendered from `final_hwra.qmd`:
1. Summary table of mean WUI metrics by island (gt).
2. Boxplot of wildfire risk score by island.
3. Scatterplot of NDVI cover vs risk score, colored by island.
