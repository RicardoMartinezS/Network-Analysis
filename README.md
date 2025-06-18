# Network Analysis Project

## Overview
This project focuses on network analysis using Python, specifically leveraging libraries such as NetworkX and OSMnx for creating and analyzing transportation networks. The analysis includes routing, network property evaluation, and geospatial operations such as buffering and intersection with building data.

## Project Structure

- `requirements.txt`: Lists the dependencies required for the project.
- `network-analysis.ipynb`: A Jupyter notebook for interactive code execution and analysis steps.

## Setup Instructions
1. Clone the repository or download the project files.
2. Navigate to the project directory.
3. Install the required dependencies using pip:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter notebook `network-analysis.ipynb` to interactively run the analysis.
2. The notebook contains markdown cells with explanations and code cells for executing the analysis steps.
3. You can modify the parameters in the notebook to analyze different areas or routing scenarios.

## Tasks
### Extending Your Analysis
1. **Create a 50 m buffer around the route**: This can be done using the `buffer` method from GeoPandas on the route geometry.
2. **Select buildings intersecting the buffer**: Use the `intersects` method to filter buildings that fall within the buffer zone.
3. **Count buildings**: Utilize the `value_counts` method to count buildings by their tags and get the total count.
4. **Export results**: Save the filtered buildings to a GeoJSON file using the `to_file` method from GeoPandas.

## Conclusion
This project serves as a comprehensive guide to performing network analysis in Python, with a focus on geospatial data. The provided code snippets and instructions will help you extend the analysis and gain insights from transportation networks and their surrounding environments.
