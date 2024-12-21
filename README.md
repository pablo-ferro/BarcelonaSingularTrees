# Singular Trees in Barcelona - Data Analysis and Mapping

This repository contains the code and web visualization resources for analyzing and transforming data about the most impressive and unique trees in Barcelona, Local interest trees from Barcelona dataset by Barcelona's City Hall Open Data Service. The project’s goal is to make this data accessible to the public through an interactive map and data visualizations on a website.

## Features

- **Data Processing**: Cleans and organizes raw data about singular trees in Barcelona.
- **Interactive Mapping**: Visualizes tree locations on a map using their geographic coordinates (latitude and longitude in EPSG:4326 format).
- **Dynamic Visualizations**: Offers insights into tree categories (Genus) and other attributes with interactive charts.
- **Public Accessibility**: Makes the data available on a user-friendly website with tooltips showing tree names and other relevant details.

## Data Source

The dataset includes fields such as:
- `name`: Tree name (displayed in tooltips for user interaction).
- `geo_epgs_4326_lat` and `geo_epgs_4326_lon`: Geographic coordinates for mapping.
- Additional metadata for categorization and analysis.

## Goals

1. **Promote Awareness**: Highlight the significance of Barcelona’s unique trees.
2. **Enable Exploration**: Provide a platform where users can explore the data interactively.
3. **Support Research**: Facilitate further analysis and research on urban greenery.

## How It Works

1. **Data Ingestion**: Load the dataset in CSV format.
2. **Data Transformation**: Clean and structure the data for visualization.
3. **Website Integration**: Use mapping libraries (e.g., Leaflet, Mapbox) and charting tools (e.g., Chart.js, D3.js) to build an engaging interface.

## Future Enhancements

- Expand datasets to include more tree attributes or additional urban greenery in Barcelona.
- Introduce filtering and search capabilities for better user interaction.
- Add mobile-friendly UI optimizations.

## Contribution

Contributions are welcome! If you have ideas for improving the project or notice issues, feel free to submit a pull request or open an issue.  

---

Explore the beauty and diversity of Barcelona’s urban forest with this project!
