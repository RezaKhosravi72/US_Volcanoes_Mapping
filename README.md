# World Population and US Volcanoes Mapping

## Overview

This project focuses on visualizing data related to US volcanoes using Python and the Folium library. It reads volcano data from a CSV file and creates an interactive map that displays the locations of volcanoes along with their elevations.

## Datasets

The project uses two datasets:

volcanoes.txt - Contains latitude, longitude, name and elevation data for US volcanoes.

world.json - GeoJSON data containing country boundaries and population figures from 2005.

## Requirements

Python 3
Folium
Pandas

## Installation

To run this project, you need to have Python installed on your system. Additionally, you'll need to install the following libraries:

- Folium
- Pandas

You can install these libraries using pip:

```bash
pip install folium pandas
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your_username/us-volcanoes-mapping.git
```

2. Navigate to the project directory:

```bash
cd us-volcanoes-mapping
```

3. Run the Python script `us_volcanoes_mapping.py`:

```bash
python us_volcanoes_mapping.py
```

4. After running the script, a file named `World_Population_&_US_Volcanoes.html` will be generated in the project directory. Open this HTML file in a web browser to view the interactive map.

## Project Structure

- `us_volcanoes_mapping.py`: Python script containing the code for reading volcano data, creating the map, and saving it to an HTML file.
- `Volcanoes.txt`: CSV file containing data about US volcanoes.
- `world.json`: GeoJSON file containing world population data used for visualizing world population on the map.

## Features

- **Map Visualization**: The project creates an interactive map using Folium, displaying the locations of US volcanoes along with their elevations.
- **Marker Color Coding**: Volcano markers are color-coded based on elevation, providing visual cues for different elevation ranges.
- **Layer Control**: The map includes a layer control feature that allows users to toggle between viewing US volcanoes and world population data.


## Potential Enhancements

Allow filtering volcanoes by characteristics
Add tooltip/legend for population overlay
Use choropleth instead of heatmap for population
Add timestamp animation for time-series population data

## Usage

The map visualizes the spatial distribution of US volcanoes and compares their locations globally against population centers. This interactive analysis could provide geological/demographic insights.
