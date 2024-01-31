# Astronomical Data Visualization
This repository contains a Jupyter Notebook (ipynb) named "astronomical_data_visualization.ipynb" that explores and visualizes astronomical data related to stars, showcasing the power of Python visualization libraries Matplotlib and Seaborn. The dataset includes information on absolute temperature, relative luminosity, relative radius, absolute magnitude, star color, spectral class, and star type.

## Observations
1. The dataset consists of 240 rows with 6 feature columns and 1 target column.
   - Absolute Temperature (in K)
   - Relative Luminosity (L/Lo)
   - Relative Radius (R/Ro)
   - Absolute Magnitude (Mv)
   - Star Color
   - Spectral Class
   - Star Type (Target classes)

   Where Lo = 3.828 x 10^26 Watts (Avg Luminosity of Sun) and Ro = 6.9551 x 10^8 m (Avg Radius of Sun).

2. Two categorical features (object type) requiring encoding:
   - Star Color
   - Spectral Class

3. Star types mapping:
   - 0 → Brown Dwarf
   - 1 → Red Dwarf
   - 2 → White Dwarf
   - 3 → Main Sequence
   - 4 → Supergiants
   - 5 → Hypergiants

## Visualizations
- Bar plot: Visualize star count per star type.
- Boxplot, Line Chart, Pair Plot, Scatter plot of HR Diagram.

## Usage
1. Clone the repository.
2. Install the required libraries: `pip install -r requirements.txt`.
3. Open the Jupyter Notebook: `jupyter notebook astronomical_data_visualization.ipynb`.
4. Explore the visualizations and observations.

Feel free to contribute or provide feedback!
