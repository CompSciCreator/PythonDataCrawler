# Detroit Mapping with ipyleaflet

[ipyleaflet](https://ipyleaflet.readthedocs.io/en/latest/index.html) is a mapping library for python built off of [Leaflet](https://leafletjs.com/). Our goal in this project is to learn the mapping library and implement a population density map along with other features in the area of Detroit, MI.

## Environment

Extract the zip contents into a folder with any name.

Ensure that you have a Jupyter Notebook environment to run the .ipynb file.

Jupyter Notebooks is available as an [IDE](https://jupyter.org/) or [VSCode extension](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).

## Required Dependencies

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install ipyleaflet in your python environment.

```bash
pip install ipyleaflet
```

Click for [more info](https://code.visualstudio.com/docs/python/environments) on VSCode virtual environments.

## Usage

```python
# main imports in our program
import csv
import json
from ipyleaflet import Map, GeoJSON, LayersControl

center = (42.3314, -83.0458) #Detroit Latitude and Longitude
map = Map(center=center, zoom=12) #Set map display to coordinates (center), set zoom to 12

display(map) #Function displaying the declared map variable
```

Each code cell displays our research and progress on the project with runnable segments. The last cell in the file is the most up-to-date application test.