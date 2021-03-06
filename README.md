# Accessing Data with Python Guide
This repository contains detailed instructional notebooks which examine a wide array of data formats using `python3` modules. I have created a notebook for each data format/theme within the `notebooks` directory of this repo. The notebooks will attempt to go through the process of reading in, exploring, manipulating and exporting the data format of interest. The following data formats are currently available;

**Common formats**

- EXCEL (.xlsx, .xls)
- CSV (.csv, .tsv, .psv)
- JSON (.json)

**Markup Languages**

- HTML (.html, .htm)
- XML (.xml)

**Geography**

- SHAPEFILE (.shp)

**Media**

- IMAGE (.jpg, .jpeg, .png, .bmp, .tiff)
- VIDEO (.mp4, .avi)

**Databases**

- SQL (sqlite, PostgreSQL, MySQL, Microsoft SQL Server, Oracle Server)
- NOSQL (MongoDB)


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
virtualenv --python=/usr/bin/python3 name_of_virtualenv
```

**Activate venv**

```sh
# activate using source command
source name_of_virtualenv/bin/activate
```

**Python requirements**

```sh
pip install pandas opencv-python lxml bs4 fiona descartes matplotlib jupyter
```

# Formats
The following data formats are available in this guide.

|Data format|Repo location|Link|Available| 
| ----- | ----- | ----- | ----- |
|EXCEL|`notebooks/EXCEL.ipynb`|[click here](https://github.com/danielc92/python-data-guide/blob/master/notebooks/EXCEL.ipynb)|`yes`|
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
- [flights database file](https://www.dropbox.com/s/a2wax843eniq12g/flights.db?dl=0)
- [illegal tipping video (youtube)](https://www.youtube.com/watch?v=pTXQXp1mDkQ)
- [Image from Pixabay](https://pixabay.com/photos/image-statue-brass-child-art-1465348/)

**Documentation Sources**

- [`pandas` library](https://pandas.pydata.org/pandas-docs/stable/)
- [`cv2` library](https://opencv-python-tutroals.readthedocs.io/en/latest/index.html)
- [`fiona` library](https://pypi.org/project/Fiona/)
- [SQLite DB](https://www.sqlite.org/draft/docs.html)
- [`pymongo` library](https://api.mongodb.com/python/current/)
- [`bs4` library](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
