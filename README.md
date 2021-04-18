# Connectome Plotter

## Installation

Just install the requirements using pip. 

`pip install -r requirements.txt`

Its recommended to install this unsing a virtual environment.

## How to use

Just save csv files to do a connectome plot inside `input` dir. 
The csv files must have the following format:

`<node_number>_vs_<node_number>;<value>`

The `<node_number>` are the number of row in the atlas file `Node_AAL116.node`.
Remember to put a `_vs_` between numbers.
