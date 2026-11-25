# Automotive Advanced Data Visualization

## Project Overview

This project presents an advanced data visualization and decision-making analysis of an automobile dataset using Python. The objective is to identify important relationships between vehicle characteristics, pricing, performance, fuel economy, body style, drivetrain, and manufacturer positioning.

The analysis focuses on converting exploratory data patterns into actionable automotive business insights that can support product positioning, pricing analysis, competitor benchmarking, and powertrain strategy.

## Dataset

The project uses the UCI Automobile dataset containing **205 vehicle records and 26 variables**.

After removing records without a valid target price, **201 vehicles** were available for price-based analysis.

### Key variables analyzed

- Price
- Engine size
- Horsepower
- Curb weight
- Highway MPG
- City MPG
- Fuel type
- Body style
- Drive wheels
- Manufacturer
- Vehicle dimensions

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook
- UCI Machine Learning Repository

## Analysis Approach

The project followed these major stages:

1. Dataset acquisition and inspection
2. Data quality assessment
3. Missing-value and duplicate analysis
4. Correlation analysis
5. Advanced exploratory visualization
6. Price segmentation
7. Manufacturer benchmarking
8. Performance-efficiency analysis
9. Budget vs Premium comparison
10. Automotive business interpretation and recommendations

## Key Findings

### Strongest relationships with price

| Relationship | Correlation |
|---|---:|
| Engine size vs Price | +0.872 |
| Curb weight vs Price | +0.834 |
| Horsepower vs Price | +0.811 |
| Highway MPG vs Price | -0.705 |
| City MPG vs Price | -0.687 |

Engine size showed the strongest positive relationship with price, followed by curb weight and horsepower.

### Performance-efficiency trade-off

Horsepower and highway fuel economy showed a correlation of **-0.771**, indicating a strong negative relationship in the dataset. Vehicles with higher horsepower generally showed lower highway MPG.

### Budget vs Premium segmentation

Compared with the Budget segment, the Premium segment showed:

- **199.7% higher median price**
- **107.4% higher median horsepower**
- **71.7% larger median engine size**
- **54.8% higher median curb weight**
- **34.2% lower highway MPG**

This indicates that premium positioning is associated with substantially greater performance and vehicle size, while also involving a clear fuel-efficiency trade-off.

### Manufacturer positioning

The highest median manufacturer price was observed for **Jaguar at 35,550**, while the lowest was observed for **Chevrolet at 6,295**, creating a median price difference of **29,255**.

## Visualizations

The final report uses nine key visualizations:

1. Engine Size, Horsepower and Curb Weight vs Price
2. Highway MPG vs Price by Fuel Type
3. Price Distribution by Body Style
4. Manufacturer Price Positioning
5. Horsepower vs Highway MPG Trade-off
6. Automotive Feature Correlation Heatmap
7. Manufacturer Price–Performance Positioning Map
8. Budget vs Premium Segment Profile
9. Budget to Premium Percentage Change

Each visualization is interpreted in terms of its analytical finding and potential automotive business implication.

## Business Applications

The findings can support:

- Vehicle price and market-position benchmarking
- Product portfolio segmentation
- Competitor analysis
- Performance-oriented product positioning
- Powertrain strategy
- Fuel-efficiency trade-off assessment
- Manufacturer-level market benchmarking

## Project Files

- `Week4_Advanced_Automotive_Data_Visualization.ipynb` — Complete Python analysis and visualizations
- `automobile_week4_raw_dataset.csv` — Original dataset used for analysis
- `week4_final_visualization_index.csv` — Final visualization index used for the report

## Limitations

The dataset contains a relatively small number of vehicles and represents a specific historical automobile dataset rather than the current global automotive market. Correlations identify statistical relationships but do not establish causation. Manufacturer and vehicle-category comparisons should also consider sample-size differences and additional commercial factors not included in the dataset.

## Conclusion

The analysis demonstrates how advanced data visualization can transform vehicle-level data into decision-support insights. The strongest pricing relationships were associated with engine size, curb weight, and horsepower, while the performance-efficiency analysis highlighted a substantial trade-off between horsepower and highway fuel economy. Segment and manufacturer analysis further demonstrated how vehicle characteristics vary across different market positions.

Overall, the project provides a data-driven framework for automotive pricing analysis, product positioning, competitor benchmarking, and strategic decision-making.

## Author

**Aaradhya Minajgi**

Automotive Data Analyst Intern Project — Week 4
