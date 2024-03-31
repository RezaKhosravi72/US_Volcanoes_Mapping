# US Volcanoes Mapping

This project aims to visualize and map the locations of volcanoes across the United States. It utilizes Python libraries folium for interactive mapping and pandas to parse volcano data from a CSV file.

## Data

The volcano data is sourced from a CSV file titled "Volcanoes.txt". This contains fields like name, location, elevation etc. of different volcanoes. 

## Requirements

- Python 3
- Folium 
- Pandas

## Instructions

1. Clone this repository
2. Navigate to project directory
3. Install requirements - `pip install -r requirements.txt`
4. Run Jupyter notebook - `jupyter notebook`
5. Run the cells in US_Volcanoes_Characteristics.ipynb
6. This will generate a HTML file with an interactive map

## Working

The notebook reads the CSV data, extracts relevant columns like latitude, longitude, name and elevation. It then maps these locations on a Folium map with color coded markers representing elevation. 

On hovering over each marker, a popup displays the volcano name. The maximum elevation is also calculated to determine marker color ranges.

## Output

Upon running all cells, my_address.html is generated containing an interactive map visualization of the volcanoes. Users can pan/zoom the map and view volcano details.

## Scope for Improvement

- Add additional volcano fields to marker popups
- Plot elevation as choropleth or heat map overlay  
- Allow downloading mapped data
- Interface to add/edit volcano entries
