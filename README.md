# indicium-ds-rental-pricing-challenge
Projeto de Data Science para o desafio de cientista de dados da Indicium.

Análise exploratória e modelo preditivo para precificação de aluguéis temporários em Nova York.

Abaixo seguem as instruções em inglês

# Data Science Challenge - Short-Term Rental Pricing

This repository contains the solution for the proposed Data Science challenge, involving short-term rental pricing in New York. The solution includes an exploratory data analysis, the construction of a price prediction model, and the evaluation of this model.

## Repository Structure

- **/** Jupyter notebooks containing exploratory analysis and model construction.
- **/data**: Folder containing the CSV file with training data.
- **/models**: Folder to store the trained model in .pkl format.
- **/reports**: PDF reports of exploratory analyses.
- **/requirements**: Requirements file.

## Prerequisites

- Python 3.x
- Packages listed in the requirements.txt file. You can install them using the command `pip install -r requirements.txt`.

## How to Run

1. Clone the repository: `git clone https://github.com/FelipiFreo/indicium-ds-rental-pricing-challenge.git`
2. Enter indicium_ds_rental_pricing_challenge.ipynb
3. Install dependencies: `pip install -r requirements.txt`
4. Run the notebooks in the desired order.

## Exploratory Analysis Results

During the exploratory analysis of the data, several essential patterns and trends were observed. Below are some of the key results:

### Price Distribution

The price distribution revealed a concentration in specific ranges, indicating potential pricing patterns. Additionally, the presence of outliers that may influence analyses was identified.

### Relationship between Availability and Price

Analyzing the relationship between availability throughout the year and prices unveiled distinct correlations in different neighborhoods. Observing seasonal variations in prices based on availability suggests a significant impact on pricing.

**Insights:**

1. *Seasonal Variations:* Clear price variations concerning availability throughout the year were noted. Price peaks may be associated with periods of high demand, such as tourist seasons or special events.

2. *Differences between Neighborhoods:* The analysis revealed that the relationship between availability and price can vary considerably between neighborhoods. Some neighborhoods may exhibit a stronger correlation, while others may show a less pronounced influence.

3. *Potential Impact on Pricing Strategy:* Understanding these correlations is crucial for developing more efficient pricing strategies. Adapting the strategy based on the specific relationship in each neighborhood allows for a more precise approach to price definition.

### Word Cloud of Location Names

The word cloud generated from location names provided interesting insights, revealing frequent words such as Manhattan, Brooklyn, etc. These associations may indicate creative patterns influencing the perception of location value.

**Insights:**

1. *Location for Investment:* The "Average Price per Neighborhood" bar chart suggests where it would be more advisable to invest based on average prices, highlighting neighborhoods with higher and lower prices.

2. *Impact of Minimum Nights and Availability:* The heatmap shows the correlation between minimum nights, availability, and price. Stronger correlations indicate a more significant impact on the price.

3. *Pattern in Location Name Text:* The word cloud helps identify common words in higher-value locations, providing insights into possible naming patterns.

### Price Suggestion for the Provided Apartment

Based on the characteristics provided for a specific apartment, the suggested price calculated using the trained model was $190.30. This estimate considers the neighborhood, minimum number of nights, and availability throughout the year.

You can explore the entire project and access the code in the "indicium_ds_rental_pricing_challenge.ipynb" file. Feel free to provide feedback!
