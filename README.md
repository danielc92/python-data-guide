# Accessing Data with Python Guide
This repository contains detailed instructional notebooks which examine various well known data formats using `python 3.7`. I have setup a notebook for each data format within the `notebooks` directory of this repo. The notebooks will attempt to go through the process of reading in, exploring, manipulating and exporting the data format of interest. The follow data formats are currently supported;

**Common text formats**

- CSV (.csv, .tsv, .psv)
- JSON (.json)

**Markup Languages**

- HTML (.html, .htm)
- XML (.xml)

**Geographic**

- SHAPEFILE (.shp)

**Media**

- IMAGE (.jpg, .jpeg, .png)
- VIDEO (.mp4, .webm)

**Databases**

- SQL (sqlite, postgres, mysql, mssql server, oracle server)
- NOSQL (mongodb)


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
- `notebooks/XML.ipynb`
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
- [XML file source](https://data.gov.au/dataset/ds-dga-4b7b5b50-774f-4416-90ce-5b7df85ff8ce/details?q=XML)