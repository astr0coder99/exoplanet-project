# Exoplanet Project

Analyze data from the NASA Exoplanet Archive to explore confirmed exoplanets and their properties.

## Project Goals
-Use Python to clean and organize exoplanet data for analysis.

-Search for patterns and trends that could help explain how planets form or behave in other solar systems.

-Investigate how key features like planet size, orbit length, and other factors relate to habitability.

-Gain hands-on experience in data science and astronomy by working with real data.

## How to Use
1. Clone this repository or download the ZIP
2. Open the (`Nasa_Dataset_Filtered_(3003_planets).ipynb`) notebook using [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/)
3. Run the cells to explore the data and analysis

## Data Source
-The dataset is sourced from the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/).  
-A cleaned and filtered version (`Nasa_Dataset_Filtered_(3003_planets).csv`) is included in this repository which contains ~3,000 planets selected for having valid and relevant features used in the habitability scoring system.

## Habitability Scoring
This project calculates a habitability score for each planet based on a custom formula using available features like:
- Orbital period (10% of the score)
- Planet radius (25% of the score)
- Equilibrium Temperature (15% of the score)
- Surface temperature (15% of the score)
- Stellar insolation (25% of the score)
- Eccentricity and mass (when available) (10% of the score)

Each planet is scored from 0 to 10, with the baseline of Earth being 10 and categorized as:
- High Habitability (8–10)
- Moderate Habitability (6–8)
- Low Habitability (<6)

After scoring, the top 100 planets are selected and ranked by habitability.

## Tools & Technologies
- Python (pandas, matplotlib, seaborn, numpy)
- Jupyter Notebook / Google Colab

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
