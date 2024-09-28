# COVID-19 Spread Analysis and SIR Model Comparison

## Project Overview

This project visualizes the global spread of COVID-19, focusing on tracking the number of **infected**, **recovered**, and **susceptible** cases. Additionally, the project compares real-world data with predictions made by the **SIR (Susceptible-Infectious-Recovered)** model to evaluate its accuracy in predicting the pandemic's spread.

Using real-world data, the SIR model is fitted and tested to examine how well it predicts infection rates and trends. The project helps understand both the potential and limitations of using the SIR model in real-world pandemic scenarios.

## Table of Contents

- [Data Sources](#data-sources)
- [The SIR Model](#the-sir-model)
- [Visualizations](#visualizations)
- [Results and Findings](#results-and-findings)


## The SIR Model

The **SIR model** is a simple but powerful epidemiological model used to simulate the spread of infectious diseases. It divides the population into three compartments:
1. **S (Susceptible)**: Individuals who can contract the disease.
2. **I (Infectious)**: Individuals who are infected and can transmit the disease.
3. **R (Recovered)**: Individuals who have recovered from the disease and are immune.

### Model Equations:
- \(\frac{dS}{dt} = -\beta \cdot S \cdot I / N\)
- \(\frac{dI}{dt} = \beta \cdot S \cdot I / N - \gamma \cdot I\)
- \(\frac{dR}{dt} = \gamma \cdot I\)

Where:
- \(\beta\) is the transmission rate.
- \(\gamma\) is the recovery rate.
- \(N\) is the total population.

The SIR model helps us estimate how a disease spreads over time and predict the number of susceptible, infected, and recovered individuals.

## Visualizations

The project includes several data visualizations to explore the COVID-19 spread and compare real-world data with the SIR model predictions:

1. **Global Time-Lapse of COVID-19 Spread**:
   - Visualizes the progression of COVID-19 infections, recoveries, and susceptible populations over time for various countries.

2. **Comparison of Real Data and SIR Model Predictions**:
   - Line charts and scatter plots compare real-world COVID-19 data with the SIR model’s predicted outcomes.
   - Parameters like transmission rate (\(\beta\)) and recovery rate (\(\gamma\)) are adjusted to fit real data.

3. **SIR Model Sensitivity Analysis**:
   - Visualizes how different values of \(\beta\) and \(\gamma\) affect the spread of the disease.

## Results and Findings

Through this analysis, we found:

The **SIR model performs reasonably well** during the early phases of the pandemic, where infection rates follow predictable patterns.





 
