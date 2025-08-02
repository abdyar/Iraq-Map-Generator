# Iraq-Map-Generator

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Version](https://img.shields.io/github/v/tag/abdyar/Iraq-Map-Generator)

A Python project to generate a detailed, game-ready map of Iraq for the OpenFront engine. The project provides a complete, configurable solution for creating a map image and bot placement JSON file.

This project is a major update to the Iraq Map Generator, now offering a highly configurable workflow. It uses GeoPandas and Matplotlib to create a pixel-perfect PNG map and a companion `bots.json` file, all based on a single `config.json` file for easy customization.

## Prerequisites

To run this script, you'll need to have Python and the necessary libraries installed. The easiest way to set up the environment is by using the provided `requirements.txt` file.

* **Python 3.x**
* **Libraries:** Install the necessary Python packages using pip:
    ```bash
    pip install -r requirements.txt
    ```

## Data Setup

This script requires three shapefiles from Natural Earth Data. You must download and unzip the contents of all three files into the **same folder** as the script, the `config.json` file, and the `requirements.txt` file.

1.  **Countries:** [Download 10m Admin 0 – Countries](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/10m-admin-0-countries/)
2.  **Rivers and Lake Centerlines:** [Download 10m Rivers + Lake Centerlines](https://www.naturalearthdata.com/downloads/10m-physical-vectors/10m-rivers-lake-centerlines/)
3.  **Lakes and Reservoirs:** [Download 10m Lakes](https://www.naturalearthdata.com/downloads/10m-physical-vectors/10m-lakes/)

## Usage

1.  Place the `make_iraq_map.py` script and `config.json` file in the same folder as all the unzipped shapefile data.
2.  (Optional) Edit the `config.json` file to customize map dimensions, colors, or bot locations.
3.  Open your terminal or command prompt.
4.  Navigate to the project folder using the `cd` command. For example:
    ```bash
    cd C:\Users\abdul\Documents\iraq_map_project
    ```
5.  Run the script with the following command:
    ```bash
    python make_iraq_map.py
    ```

The script will generate both `iraq_openfront_map.png` and `bots.json` in the same directory.

## Example Output

The generated image and JSON file are ready to be imported into the OpenFront game.

<img width="1144" height="649" alt="Screenshot 2025-08-02 121639" src="https://github.com/user-attachments/assets/37f8337a-cd4d-4e66-beb2-7be18480acea" />

