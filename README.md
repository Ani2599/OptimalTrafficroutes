# Optimal Traffic Routes Prediction for Shuttle Service

This project predicts optimal traffic routes for shuttle services using a graph-based approach. It visualizes traffic routes, calculates shortest paths, and applies the Louvain community detection algorithm for partitioning traffic routes into clusters.

## Features
- **Traffic Route Graph**: Visualizes shuttle routes as a graph, where nodes represent locations, and edges represent routes.
- **Louvain Community Detection**: Identifies communities within the network of routes for optimal shuttle services.
- **Shortest Path Calculation**: Determines the shortest routes based on given traffic data.
- **Edge Betweenness Centrality**: Identifies critical connections in the traffic network.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ani2599/OptimalTrafficroutes.git
   ```

2. Navigate into the project directory:
   ```bash
   cd OptimalTrafficroutes
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. To run the application:
   ```bash
   streamlit run app.py
   ```

## Files

- **app.py**: Main Streamlit application for predicting optimal shuttle routes.
- **Community_List_snippet.csv**: Sample data for testing the traffic network.
- **final (2).xlsx**: Traffic data in Excel format used for analysis.
- **requirements.txt**: List of required Python packages.
- **Procfile**: For deployment in Heroku.
- **setup.sh**: Setup script for the environment.
- **streamlite.csv**: Data file used in the application.

## Usage

1. Upload an Excel file containing traffic data with columns for origin, destination, and other relevant attributes like duration and distance.
2. Visualize the traffic route graph and community partitions.
3. Calculate the best route and shortest path for shuttle services.

## Contributing

Feel free to fork this repository and submit pull requests. Contributions are welcome to improve the model and functionalities.

