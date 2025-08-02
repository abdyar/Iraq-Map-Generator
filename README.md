# Iraq-Map-Generator
A Python script to generate a detailed map of Iraq using GeoPandas, Matplotlib, and Natural Earth data. Visualizes country borders, major rivers, and lakes from public shapefiles.

This project contains a Python script that generates a detailed map of Iraq, highlighting its borders, major rivers, and lakes. The script uses the GeoPandas and Matplotlib libraries, and it relies on publicly available geographic data from Natural Earth.

## Prerequisites

Before running the script, you'll need to have Python and a few libraries installed.

* **Python 3.x**
* **Libraries:** Install the necessary Python packages using pip:
    ```
    pip install geopandas matplotlib shapely
    ```

## Data Setup

This script requires three shapefiles from Natural Earth Data. You must download and unzip the contents of all three files into the **same folder** as the `make_iraq_map.py` script.

1.  **Countries:** [Download 10m Admin 0 – Countries](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/10m-admin-0-countries/)
2.  **Rivers and Lake Centerlines:** [Download 10m Rivers + Lake Centerlines](https://www.naturalearthdata.com/downloads/10m-physical-vectors/10m-rivers-lake-centerlines/)
3.  **Lakes and Reservoirs:** [Download 10m Lakes](https://www.naturalearthdata.com/downloads/10m-physical-vectors/10m-lakes/)

## Usage

1.  Place the `make_iraq_map.py` script in the same folder as all the unzipped shapefile data.
2.  Open your terminal or command prompt.
3.  Navigate to the project folder using the `cd` command. For example:
    ```
    cd C:\Users\abdul\Documents\iraq_map_project
    ```
4.  Run the script with the following command:
    ```
    python make_iraq_map.py
    ```

The script will execute and save the resulting map as a PNG file named `iraq_map.png` in the same directory.

## Example Output

The generated image will be a map of Iraq with its geographical boundaries outlined, and the country's major rivers and lakes drawn in blue.nd lakes drawn in blue.

<img width="637" height="637" alt="Screenshot 2025-08-02 113338" src="https://github.com/user-attachments/assets/740a1617-8691-4880-ad03-74b61b57fa5b" />

