# Accessing Data with Python Guide
This repository contains detailed instructional notebooks which examine various well known data formats using `python 3.7` modules exclusively. I have setup a notebook for each data format within the `notebooks` directory of this repo. The notebooks will attempt to go through the process of reading in, exploring, manipulating and exporting the data format of interest. The following data formats are currently included;

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

**Create virtual environment called 'venv'**

```sh
# specify the python path which was collected above
virtualenv --python=/usr/bin/python3 venv
```

**Activate venv**

```sh
# activate using source command
source venv/bin/activate
```

**Python requirements**

```sh
pip install pandas opencv-python lxml bs4 fiona descartes matplotlib jupyter
```

# Formats
The following data formats are available in this guide.

|Data format|Repo location|Link|Available| 
| ----- | ----- | ----- | ----- |
|CSV|`notebooks/CSV.ipynb`|[click here](https://github.com/danielc92/python-data-guide/blob/master/notebooks/CSV.ipynb)|`yes`|
|JSON|`notebooks/JSON.ipynb`|[click here](https://github.com/danielc92/python-data-guide/blob/master/notebooks/JSON.ipynb)|`yes`|
|HTML|`notebooks/HTML.ipynb`|[click here](https://github.com/danielc92/python-data-guide/blob/master/notebooks/HTML.ipynb)|`yes`|
|XML|`notebooks/XML.ipynb`|[click here](https://github.com/danielc92/python-data-guide/blob/master/notebooks/XML.ipynb)|`yes`|
|Shapefile|`notebooks/Shapefiles.ipynb`|[click here](https://github.com/danielc92/python-data-guide/blob/master/notebooks/Shapefiles.ipynb)|`yes`|
|IMAGE|`notebooks/IMAGE.ipynb`|[click here](https://github.com/danielc92/python-data-guide/blob/master/notebooks/IMAGE.ipynb)|`yes`|
|VIDEO|`notebooks/VIDEO.ipynb`|[click here](https://github.com/danielc92/python-data-guide/blob/master/notebooks/VIDEO.ipynb)|`yes`|
|SQL|`notebooks/SQL.ipynb`|[click here](https://github.com/danielc92/python-data-guide/blob/master/notebooks/SQL.ipynb)|`yes`|
|NOSQL|`notebooks/NOSQL.ipynb`|[click here](https://github.com/danielc92/python-data-guide/blob/master/notebooks/NOSQL.ipynb)|`yes`|

# Contributors
- Daniel Corcoran

# Sources
**Data Sources**

- [XML file source](https://data.gov.au/dataset/ds-dga-4b7b5b50-774f-4416-90ce-5b7df85ff8ce/details?q=XML)
- [Shapefiles for Australia 2018 release by ABS](https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.003July%202018?OpenDocument)

**Documentation Sources**

- [`pandas` library](https://pandas.pydata.org/pandas-docs/stable/)
- [`cv2` library](https://opencv-python-tutroals.readthedocs.io/en/latest/index.html)
- [`fiona` library](https://pypi.org/project/Fiona/)
- [SQLite DB](https://www.sqlite.org/draft/docs.html)
- [`pymongo` library](https://api.mongodb.com/python/current/)
- [`bs4` library](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
