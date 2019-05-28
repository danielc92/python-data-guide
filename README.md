# Data Guide
Setting up notebooks in order to explore data from a large variety of formats using purely `python`.

# Setup
**Setting up virtual environment (python 3.7)**
Get location of bin file 
```sh
which python3
```

Create virtual environment called 'venv'
```sh
virtualenv --python=/usr/bin/python3 venv
```

Activate venv 
```sh
source venv/bin/activate
```

*Python requirements**
```sh
pip install pandas opencv-python 
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
- No notebook as of now.
### SQL
- No notebook as of now.
### NOSQL
- No notebook as of now.


# Contributors
- Daniel Corcoran

# Sources
- [Shapefiles for Australia 2018 release by ABS](https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.003July%202018?OpenDocument)