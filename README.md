# Clustering Countries Based on Socio-Economic Metrics

## Problem Statement
Identifying countries in need based on socio-economic and health metrics is paramount for targeted global aid and policy-making. This project utilizes unsupervised machine learning to cluster countries, ascertaining which ones require immediate assistance and which are relatively stable. The aim is to provide a data-driven approach to international aid prioritization.

## Technical Highlights and Key Learnings

- **Advanced Data Exploration**:
  - Utilized `matplotlib` and `seaborn` to visualize feature relationships, particularly between metrics like child mortality, income, GDP, exports, and health expenditure.

- **Proficient Feature Engineering**:
  - Streamlined the dataset by categorizing metrics into overarching categories: health, trade, and finance. Developed composite features by averaging related metrics.

- **Data Scaling and Dimensionality Reduction**:
  - Normalized features using `MinMaxScaler` and applied Principal Component Analysis `(PCA)` for effective dimensionality reduction.

- **Clustering and Analysis**:
  - Applied the `K-Means` clustering algorithm and strategically labeled clusters based on their developmental needs.

- **Technologies and Libraries Used**: 
  - Demonstrated proficiency with libraries such as `pandas`, `matplotlib`, `seaborn`, `sklearn`, and `yellowbrick`.

## Findings & Visualizations

The project's highlight is an interactive world map heatmap, illustrating the distribution of countries based on their clustering results. 

[Click here to explore the interactive world map heatmap!](https://KgKevin0.github.io/Clustering-Countries-In-Need/cluster_worldmap.html)

Key Insights from the heatmap:
- **Help Needed**: Regions highlighted in red represent countries facing significant socio-economic challenges, including high child mortality rates.
- **Might Need Help**: Yellow regions denote countries that, while better off than the red ones, still require assistance.
- **No Help Needed**: Green regions indicate countries that are relatively stable based on the considered metrics.

## Dataset Overview

The dataset provides a comprehensive view of countries' developmental metrics, encompassing socio-economic indicators like child mortality rate, GDP per capita, health expenditure, life expectancy, and more.

## Contribution & Feedback

Passionate about data science and continuous learning, I welcome feedback from industry professionals, recruiters, and peers. Your insights can help refine the project further. Please feel free to share your thoughts or suggestions.

## License
This project is under the MIT License. Open for sharing, adaptation, and collaboration with proper attribution.
