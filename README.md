# Species Habitat Suitability in Rwanda

This project predicts where species can live in Rwanda based on climate, elevation, and forest cover. It starts from a simple observation: far more birds are seen in western Rwanda (Rusizi) than in Kigali. Knowing which environmental conditions a species needs shows where habitat is, how well it is protected, and how forest loss and climate change may affect it, which can help guide conservation decisions.

## Research question

**Which environmental conditions (elevation, rainfall, temperature, forest cover) best predict where [species name] occurs in Rwanda, and how might its suitable habitat change with forest loss and climate change by 2050?**

## Data
Not yet done with this part; still looking for the datasets to use

## Repository structure

```
species_tracking_project/
├── README.md              Project description and instructions
├── scripts/               Python scripts for downloading data, extracting values
```

## How to run the code

The notebook was created in Google Colab and uses Python and R.

1. Open `1_data_clean.ipynb` in Google Colab.
2. Mount Google Drive when prompted (`from google.colab import drive; drive.mount('/content/drive')`) and set the data path to the folder where you saved the downloaded files.
3. Run the notebook cells in order

## Cleaning steps and known data issues

Next step when I got the datasets to use

## Status and next steps

**Done:** project set up, species records downloaded and cleaned in `1_data_clean.ipynb`.

**Next:**
1. Download and clip the climate, elevation, and forest layers to Rwanda.
2. Extract environmental values at each record, and create background points.
3. Train and compare models (Random Forest, logistic regression, MaxEnt) with spatial cross-validation.
4. Produce the habitat suitability map and the protected-area overlay.
5. Map habitat change from forest loss (2001 to 2023) and projected climate change (2041 to 2060).
