# Accessing, Modifying and Saving data using Python.
This project will go through how to deal with a wide array of datatypes using purely `python 3.7`. I have setup a notebook for each data format within the `notebooks` directory of this repo. The notebooks will attempt to go through the process of reading in, exploring and manipulating the data format of interest.

# Setup
System used in this project is *Ubuntu 19.04* with *Python 3.7* installation

**Setting up virtual environment**

```sh
# Get location of python bin file 
which python3
```

Create virtual environment called 'venv'
```sh
# specify the python path which was collected above
virtualenv --python=/usr/bin/python3 venv
```

Activate venv 
```sh
# activate using source command
source venv/bin/activate
```

*Python requirements**
```sh
pip install pandas opencv-python lxml bs4 fiona descartes matplotlib jupyter
```
# Formats
The following formats are documented in this guide.
### CSV
- `notebooks/CSV.ipynb`
### JSON
- `notebooks/JSON.ipynb`
### HTML
- `notebooks/HTML.ipynb`
### XML
- No notebook as of now.
### SHP
- `notebooks/Shapefiles.ipynb`
### VIDEO
- No notebook as of now.
### IMAGE
- `notebooks/IMAGE.ipynb`
### SQL
- `notebooks/SQL.ipynb`
### NOSQL
- `notebooks/NOSQL.ipynb`

# Contributors
- Daniel Corcoran

# Sources
- [Shapefiles for Australia 2018 release by ABS](https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.003July%202018?OpenDocument)
- [pandas documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [opencv documentation](https://opencv-python-tutroals.readthedocs.io/en/latest/index.html)
- [fiona documentation](https://pypi.org/project/Fiona/)