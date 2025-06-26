# 100 Worlds Beyond Our Sun: A Data-Driven Search for Earth 2.0
[View the full paper (PDF)][(https://docs.google.com/document/d/1UE0BB_rskslXQnqsLqtzHXGmXGiivyza0-fCwb8TW9M/edit?tab=t.0)]

This project analyzes over 38,000 confirmed and candidate exoplanets from NASA's Exoplanet Archive to identify the top 100 potentially habitable worlds. Using Python for data cleaning, filtering, and statistical analysis, the study focuses on key habitability criteria such as orbital period, planet radius, equilibrium temperature, surface temperature, and stellar insolation.

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
-The dataset is sourced from the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/), specifically from the "Confirmed Planets" table.

-A cleaned and filtered version (`Nasa_Dataset_Filtered_(3003_planets).csv`) is included in this repository which contains ~3,000 planets selected for having valid and relevant features used in the habitability scoring system.

## Habitability Scoring
This project calculates a habitability score for each planet based on a custom formula using available features like:
- Orbital period (20% of the score)
- Planet radius (25% of the score)
- Temperature-Equillibrium and surface combined (10% of the score)
- Stellar insolation (25% of the score)
- Eccentricity and mass (20% of the score)

Each planet is scored from 0 to 10, with the baseline of Earth being 10 and categorized as:
- High Habitability (7–10)
- Moderate Habitability (4–6.9)
- Low Habitability (<4)

After scoring, the top 100 planets are selected and ranked by habitability.

## Tools & Technologies
- Python (pandas, matplotlib, seaborn, numpy)
- Jupyter Notebook / Google Colab

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
