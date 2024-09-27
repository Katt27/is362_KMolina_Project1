# Airlines Delays Analysis

## Project Overview

This project analyzes the arrival delays of two airlines, Alaska Airlines and AM West Airlines, across five major U.S. cities. The goal is to compare the performance of the two airlines in terms of on-time vs delayed flights and draw insights based on the data provided.

The project uses Python and Jupyter Notebook for data analysis and visualization. The analysis includes a comparison of the two airlines' performance across different cities and the percentage of delays for each airline.

## Data

The dataset provided contains the number of on-time and delayed flights for two airlines (Alaska Airlines and AM West Airlines) across five cities:
- **Los Angeles**
- **Phoenix**
- **San Diego**
- **San Francisco**
- **Seattle**

The dataset is structured as follows:

| Airline | Status  | Los Angeles | Phoenix | San Diego | San Francisco | Seattle |
|---------|---------|-------------|---------|-----------|---------------|---------|
| ALASKA  | on time | 497         | 221     | 212       | 503           | 1,841   |
| ALASKA  | delayed | 62          | 12      | 20        | 102           | 305     |
| AM WEST | on time | 694         | 4,840   | 383       | 320           | 201     |
| AM WEST | delayed | 117         | 415     | 65        | 129           | 61      |

## Objectives

1. **Load and process the data**: Create a CSV file from the provided dataset and load it into a pandas DataFrame for analysis.
2. **Analyze and compare performance**: Compare the on-time and delayed flights for both airlines across all five cities.
3. **Visualize the results**: Create visualizations (bar charts) to illustrate the differences between on-time and delayed flights for the two airlines.
4. **Draw insights**: Provide narrative conclusions based on the analysis, such as which airline performs better overall and in specific cities.

## Tools and Libraries

The project is implemented in a Jupyter Notebook using the following libraries:
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For creating visualizations and plots.

## Analysis and Insights

### Key Observations:

- **AM West Airlines** operates a much higher number of flights, especially in Phoenix, but it also has a higher rate of delays in that city.
- **Alaska Airlines** performs more consistently across all cities, with fewer total delays compared to AM West.
- **Seattle** and **San Francisco** are strong-performing cities for Alaska Airlines in terms of on-time flights.
- **Phoenix** is a challenge for AM West, with a significant number of delays relative to the volume of flights.

### Visualizations:

The project includes visualizations that compare on-time vs delayed flights for each airline across the cities.

## How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Katt27/airlines-delays-analysis.git

cd airlines-delays-analysis

pip install -r requirements.txt

jupyter notebook AirplaneDelaysAnalysis.ipynb
