# Analysis of Alternative Energies in Argentina

This project analyzes a dataset on alternative energies in Argentina, using Python for data analysis and Power BI for visualization.

## Data Source

The original dataset was obtained from the [Ministry of Economy of Argentina](https://www.economia.gob.ar/catalogo-sspmi/nuevo_dataset/energias-alternativas.csv).

### Original dataset: 
energias-alternativas.csv

## Python Analysis

### Tools Used
- Google Colab
- Libraries: Python, Pandas, Matplotlib, Seaborn, CSV, IO, Numpy, Scipy

### Analysis Process
File: EDA_Alternative_Energies_Argentina_2018_2021.ipynb

1. Loading and initial exploration of the dataset (7827 rows and 14 columns).
2. Visualization of high-level information using `info()` and the first five rows using `head()`.
3. Manipulation of date values to convert them to datetime data type.
4. Checking for null values.
5. Creation of basic plots.
6. Feature engineering to create new columns, expanding the dataset to 22 columns.

### cleaned dataser: 
new_dataset.csv

### Addressed Questions
A) What is the trend regarding the amount of energy generated per year in this dataset?
B) On average, which is the month of the year in which the most energy is produced?
C) Which provinces have improved their energy production in the last year, compared to the first?

## Power BI Visualization
File: power_bi\power_bi.pbix

### Visualization Process
1. Loading the dataset into Power BI.
2. Creation of new metrics and columns using DAX.
3. Development of visualizations to correctly illustrate the different categories and values needed to solve the project questions.

### Created Visualizations
- Map plot to geolocate energy generation.
- Line plot to show average generation per month.
- Dot histogram with trend line to show total energy generation by date.
- Bar plot to show energy generation by each source.
- Bar plot to show energy generation difference between the first year and the last year by each province.
- 4 cards (KPIs) with summary data.
- 4 filters (data segmentation) to apply over the visualizations.

## How to use:
1. copy the repository.
2. run the power_bi.pbix file.

## License

Copyright (c) [2024] [GNeironiAR]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.