# Proptech in The San Francisco Market

![San Francisco](./Images/San_Francisco.jpg)

---

## Technologies


Before attempting to execute any _Python_ code in `san_francisco_housing.ipynb`, it is imperative that your development environment holds the following modules:

[os](https://docs.python.org/3/library/os.html) - Miscellaneous operating system interfaces.

[pandas](https://pandas.pydata.org/pandas-docs/stable/) - Data analysis module.

[plotly](https://plotly.com/python/) - Interactive plotting module.

[hvplot](https://hvplot.holoviz.org/) - High-level plotting API.

[pathlib](https://docs.python.org/3/library/pathlib.html) - Object-oriented filesystem path library.

[dotenv](https://pypi.org/project/python-dotenv/) - _.env_ file parser module.

---

## Installation Guide

With your _Python 3.7+_ environment, run the following commands via CLI:

```
import os
import pandas as pd
import plotly.express as px
import hvplot.pandas
from pathlib import Path
from dotenv import load_dotenv
```

---

## Examples

![Average Sale and Gross Rent](./Images/avg-sale-px-sq-foot-gross-rent.png)

![Mapbox Plot](./Images/mapbox-plot.png)

![Pricing Information by Neighborhood](./Images/pricing-info-by-neighborhood.png)

![Housing Units by Year](./Images/zoomed-housing-units-by-year.png)

---

## Usage

1. Clone repository onto your personal machine. 

2. Open _Jupyter Lab_ or _Jupyter Notebook_ via _Anaconda Navigator_ and navigate to the directory in which the file `san_francisco_housing.ipynb` is present. _All relevant code for this repository will be executed via Jupyter Notebook and no output will be printed to the command line_. Ensure that all relevant dependencies and _Python_ modules are installed (see __Technologies__ and __Installation Guide__ for more details) before attempting to execute code within _Jupyter Notebook_; otherwise, you will receive multiple interpreter errors! 

3. With the notebook open, start at the very first cell reading "__Housing Rental Analysis for San Francisco__" (a cell will be active when a rectangular border is surrounding the area in question). Run each cell in sequential order. _It is vital that all cells are ran in sequential order or your notebook will generate compiler errors_!. 

---

## Contributors

New development created by Aaron C. Montano. **Code from 'Initial commit.' commit originates from UC Berkeley Extension and I do not claim original ownership nor scholarship**.

---

## License

Software tool available for public use. 
