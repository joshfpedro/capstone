# Optimizing Disease Management in Crop Production

## Project Overview

### Problem Area
This project addresses the complex challenge of optimizing disease management strategies in hop production, with a specific focus on powdery mildew. The key issues include:

- Balancing disease control with economic profitability for farmers
- Minimizing environmental impact of disease management practices
- Understanding the interplay between disease incidence, management costs, crop yield, and market conditions

### Affected Stakeholders
- Hop farmers
- Policymakers (e.g., US Department of Agriculture)
- The broader agricultural sector and consumers of hop products

### Proposed Data Science Solution
We aim to develop a coupled epidemiological-economic model using machine learning techniques to:

1. Predict disease spread based on environmental conditions, crop susceptibility, and management practices
2. Optimize fungicide application strategies considering factors like primary inoculum dose, pathogen diversity, and market demand
3. Forecast crop yields and quality based on disease progression and management interventions
4. Simulate various scenarios to identify optimal disease management strategies that maximize profit while minimizing environmental impact

### Impact
The potential impact of this project includes:

- Significant economic savings for hop farmers through improved disease management
- Reduced environmental impact from optimized fungicide use
- Enhanced long-term sustainability of the hop industry
- Improved decision-making tools for farmers and policymakers

### Dataset Description

Our analysis utilizes a comprehensive dataset collected from hop yards in Oregon from 2014 to 2017. The dataset includes:

1. Monthly disease assessments
2. Cultivar information
3. Management practices (e.g., fungicide applications)
4. Weather data
5. Market data for hop prices and quality standards
6. Fungicide application records and costs

#### Data Dictionary

| Variable | Description | Type |
|----------|-------------|------|
| yard_id | Unique identifier for each hop yard | Integer |
| month | Month of assessment | Date |
| year | Year of assessment | Integer |
| cultivar | Hop cultivar | String |
| disease_incidence | Proportion of plants with powdery mildew | Float |
| fungicide_applications | Number of fungicide applications | Integer |
| fungicide_cost | Cost of fungicide applications | Float |
| yield | Hop yield per hectare | Float |
| cone_color | Quality measure on a 10-point scale | Integer |
| market_price | Price per unit of hops | Float |
| temperature | Average monthly temperature | Float |
| precipitation | Total monthly precipitation | Float |
| wind_speed | Average monthly wind speed | Float |

This dataset allows for a comprehensive analysis of the factors influencing hop powdery mildew epidemics and their economic impacts, enabling the development of sophisticated predictive models and optimization strategies.