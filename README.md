# Worlds Beyond Our Sun: A Data-Driven Search for Potentially Habitable Exoplanets

This project analyzes over 38,000 confirmed and candidate exoplanets from NASA's Exoplanet Archive to identify the top potentially habitable worlds. Using Python for data cleaning, filtering, and statistical analysis, the study focuses on key habitability criteria such as planet mass, planet radius, equilibrium temperature, tidal locking, and stellar flux.

## Project Goals
-Use Python to clean and organize exoplanet data for analysis.

-Search for patterns and trends that could help explain how planets form or behave in other solar systems.

-Investigate how key features like planet size, equilibrium temperature, and other factors relate to habitability.

-Gain hands-on experience in data analysis and astronomy by working with real data.

## How to Use
1. Clone this repository or download the ZIP
2. Open the (`NASA_Exoplanet_Archive_Cleaned.ipynb`) notebook using [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/)
3. Run the cells to explore the data and analysis

## Data Source
-The dataset is sourced from the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/), specifically from the "Confirmed Planets" table.

-A cleaned and filtered version (`NASA_Exoplanet_Archive_Cleaned.csv`) is included in this repository which contains ~6,000 planets selected for having valid and relevant features used in the habitability scoring system.

## Habitability Scoring
This project calculates a habitability score for each planet based on a custom formula using available features like:
- Planet Mass (20% of the score)
- Planet radius (20% of the score)
- Equilibrium Temperature (30% of the score)
- Stellar insolation (18% of the score)
- Tidal-Locking (12% of the score)

Each planet is scored from 0 to 10, with the baseline of Earth being 10 and categorized as:
- High Habitability (7–10)
- Moderate Habitability (4–6.9)
- Low Habitability (<4)

After scoring, the top planets are selected and ranked by habitability.

## Tools & Technologies
- Python (pandas, matplotlib, seaborn, numpy)
- Jupyter Notebook / Google Colab

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
