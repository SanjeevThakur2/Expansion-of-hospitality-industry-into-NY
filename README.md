# Expansion-of-hospitality-industry-into-NY
## Description:
The Expansion of Hospitality Industry into NY project aims to analyze Airbnb's listings dataset to gain insights into the vacation rental market in New York. The project uses statistical and data visualization techniques to uncover patterns and trends in the data, and develop a deeper understanding of the factors that influence the pricing of vacation rentals.

## Data Assumptions:
All units in the dataset are residential units only.
Price is equivalent to revenue.
Assumptions have been made to answer business questions with appropriate formatting and data storytelling.
The geopy module is assumed to be not installed and is included in the code. If it is already installed, please comment the first line in the Jupyter Notebook.
All questions have been answered, and the Tableau file and PPT should be reviewed in full.

## Scope:
The project is applicable only for New York State due to data limitations.
Only residential units (the type of which found in Airbnb) are covered under this analysis.
Hotels are out of scope for this dataset as the Airbnb data is from a period where they did not list hotels.

## Limitations:
Insights gathered from the Airbnb data will be subject to the same limitations within the Airbnb data.
Due to some missing values and outliers in the dataset, assumptions have been made to fill in missing values. These assumptions may not be 100% accurate.
Lack of data on residential and commercial units has forced a few assumptions to answer questions.
Getting Started:
To get started with the project, follow these steps:


Install the required Python libraries using the command 'pip install -r requirements.txt'.
Run the Jupyter Notebook to view the analysis and insights gained from the Airbnb data.
Prerequisites:
1.Python 3.x
2. Jupyter Notebook or any other Python IDE
3. numpy
4. statistics
5. pandas
6. matplotlib.pyplot
7. matplotlib.image
8. seaborn
9. warnings


## python
Copy code
import numpy as np
import statistics as st
import pandas as pd
import matplotlib.pyplot as plt
import matplotlib.image as mpimg
%matplotlib inline
import seaborn as sns
import warnings
warnings.filterwarnings('ignore')

## Usage:
To use the project, run the Jupyter Notebook and view the analysis and insights gained from the Airbnb data.

## Contributing:
Contributions to the project are welcome. Please submit a pull request with your proposed changes.

## License:
The project is released under the MIT License.

## Acknowledgments:
Airbnb for providing the listings dataset.
Python and various data analysis and visualization libraries used in the project.
