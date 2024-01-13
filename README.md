# Startup Analysis with Python

## Content of the project
The purpose of this project is to derive insightful observations from the main dataset (`Startup_Dataset.xlsx`). The questions that I try to answer are:
1) What are the most successful universities?
2) Which sectors are the most successful ones?
3) For how long should I expect to stay private?
4) What country is more suited for creating a startup?
5) How much financing am I expected to obtain?


## Instructions
The main file used for the analysis is `Startup_Dataset.xlsx`. This workbook contains four worksheets:
- COMPANY: contains information about different companies, including their category, the revenue range, and the employee count
- INVESTMENT: includes information about the financing rounds that companies in the previous sheet have gone through
- ACQUISITION: contains information about the acquisitions completed by some of the firms contained in the sheet COMPANIES
- EMPLOYEE: includes information about the University attended by professionals that work in some of the companies included in the dataset

Additionally, three csv files are needed in order to run the code properly:
- `Exchange_Rates_Table.csv`: provides information on the exchange rates of several currencies at different points in time
- `world-universities.csv`: contains a list of all of the universities in the world
- GDP Per Capita All `countries.csv`: contains a list of the GDP per capita of all of the countries in the world

When running the code, make sure that the filepath for the several read_excel and read_csv Panda functions have been updated correctly.


## Usage

To run the analysis, open the `Julian_Enciso_Final_Project.ipynb` notebook and execute each cell sequentially. Ensure that the required datasets are in the correct file paths.


## Dependencies

The following libraries are used in different parts of the project:
- Pandas
- Numpy
- Matplotlib.pyplot
- Seaborn
- Geopandas
- Display
- Combinations
- Warnings
- SettingWithCopyWarning


Proceed to their installation with the following code:

```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import geopandas as gpd
from IPython.display import display
from itertools import combinations
import warnings
from pandas.errors import SettingWithCopyWarning
```

## Installation
Ensure that you have Python installed on your system. If not, you can download it from [python.org](https://www.python.org/downloads/).


## Usage
You are allowed to view and fork the repository for personal use. If you have any questions or would like to discuss potential collaborations, feel free to reach out.


## Contributing
Although this project is not open-source, I welcome feedback, bug reports, and suggestions. If you encounter any issues or have ideas for improvements, feel free to send me an email to julian.enciso.izquierdo@gmail.com.


## License
This project is not open-source, and it does not come with a specific open-source license. All rights are reserved, and usage, modification, or distribution of the code is not permitted without explicit permission.

If you are interested in using or collaborating on this project, please send me an email to julian.enciso.izquierdo@gmail.com.

## Acknowledgments
The project uses data from Startup_Dataset.xlsx, which was kindly shared by Professor Howard Zhong. Special thanks to him for his valuable feedback.
