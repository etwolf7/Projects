# Pricing Strategy Analysis for Big Mountain Resort

## Problem Overview:
Big Mountain Resort aims to counterbalance a recent surge in operating costs by $1,540,000 this season. The challenge is to devise an effective pricing strategy that optimizes capitalization on facility investments.

## Resort Overview:
Nestled amidst the stunning landscapes of Glacier National Park and Flathead National Forest, Big Mountain Resort boasts access to 105 trails. With an annual footfall of 350,000 skiing enthusiasts, the resort seeks guidance on recalibrating ticket prices without compromising value.

## Current Pricing Approach:
Relying solely on market averages won't suffice for Big Mountain Resort to maximize capitalization and maintain a sustainable edge over competitors.

## Analyzing Scenarios:
To address the pricing challenge, the resort is exploring several options, including closing underused runs, altering the vertical drop, and expanding snow-making capabilities. A model has been developed to assess the impact of these scenarios on ticket prices and revenue.

## Feature Insights:
Through feature engineering and correlation analysis, it was discovered that factors such as fastQuads, runs, snow making acreage, and vertical drop significantly influence ticket prices. Visitors prioritize guaranteed snow coverage, and the total skiable terrain area is less influential than the area with snow-making capabilities.

## Model Development:
A linear model and a random forest model were considered, with the latter proving more robust during testing and cross-validation. The final model focuses on key features: vertical_drop, Snow Making_ac, total_chairs, fastQuads, Runs, LongestRun_mi, trams, and SkiableTerrain_ac.

## Recommendations:
The model indicates that Big Mountain Resort's current ticket prices are 16.31% lower than predicted. Potential scenarios include increasing ticket prices or reducing costs by closing runs.

- Increasing the vertical drop by 150 ft could raise ticket prices by 10.44%, resulting in a revenue increase of $14,811,594.
- Adding 2 acres of snow making may increase ticket prices by 12%, yielding a revenue increase of $17,068,841.

Regarding closing runs, the impact on revenue varies:

- Closing one run has no significant impact.
- Closing 2 runs reduces revenue by $750,000.
- Closing 3 to 5 runs results in similar revenue loss.
- Closing 10 runs reduces revenue by $3 million.

## Conclusion:
The recommended scenario for maximum revenue increase involves increasing the vertical drop, adding a chair lift, a run, and 2 acres of snow making. This could raise ticket prices by 12%, resulting in a net revenue increase of $15,528,841 after deducting operating costs. Due to data limitations, the model doesn't recommend closing runs or dynamic ticket pricing without information on operating costs per run and weekday ticket prices.
