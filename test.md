* Meta Resources
  - [Awesome Geospatial](https://github.com/sacridini/Awesome-Geospatial) 
  - [Awesome GIS](https://github.com/sshuair/awesome-gis)
  - Github Topic: [Mapping](https://github.com/topics/mapping)
  - Github Topic: [GIS](https://github.com/topics/gis)
  - Book Repo: [Python for Geospatial Data Analysis](https://github.com/datamongerbonny/Python-for-geospatial-analysis) by  Repo
* Geospatial Datasets
  - [NYC Open Data](https://opendata.cityofnewyork.us/)
  - [SFData](https://datasf.org/opendata/)
  - [MassGIS](http://giswebservices.massgis.state.ma.us/geoserver/wfs?version=1.0.0)
  - [World Resources Institute](https://www.wri.org/data)
  - [OpenStreetMap](https://www.openstreetmap.org/#map=5/38.007/-95.844): OpenStreetMap is a free, editable map of the whole world that is being built by volunteers largely from scratch and released with an open-content license.
    * [Keys](https://taginfo.openstreetmap.org/keys): All tag keys that exist in the database or in any of the other sources
    * [wiki](https://wiki.openstreetmap.org/wiki/Buildings): The OpenStreetMap Wiki (this website) is a place for help documentation, technical documentation and promotional material on everything related to the OpenStreetMap project.
  - [NLCD 2016 National Landcover Database](https://developers.google.com/earth-engine/datasets/catalog/USGS_NLCD_RELEASES_2016_REL?hl=en#description) (via Google Earth Engine Data Catalog)
  - [Natural Earth Data](https://www.naturalearthdata.com/)
  - [Uber Movement Databases](https://movement.uber.com/) 
* Geospatial Utilities
  - [Missingno](https://github.com/ResidentMario/missingno): Identify and clean missing data
  - [EarthExplorer ](https://earthexplorer.usgs.gov/)(USGS)
  - [Copernicus.eu](https://scihub.copernicus.eu/) 
* Mapping Choices: Canned Applications
  - Application: Commercial 
    * ArcGIS: Most advanced (and expensive?) Geospatial software product.
    * [Here](https://developer.here.com/): Build location-aware apps and services using the world’s #1 location platform
    * Tableau: Top BI Data Visualization Platform (incl Geospatial Mapping)
  - Application: Freemium
    * [Google Earth Engine Code Editor](https://code.earthengine.google.com/)
  - Application: Open Source
    * [QGIS](https://www.qgis.org/en/site/): QGIS is a professional GIS application that is built on top of and proud to be itself Free and Open Source Software (**FOSS**). You can v**isualize, manage, edit, analyze data, and compose** printable maps.
* Mapping Choices: Python & Jupyter		
  - Python
    * [GeoPy](https://github.com/geopy/geopy): Makes it easy for Python developers to **locate the coordinates** of addresses, cities, countries, and landmarks across the globe using several third-party geocoders and other data sources.
    * [GeoPandas](https://geopandas.org/en/stable/): Extends the datatypes used by **pandas **to allow **spatial operations on geometric types**. Geometric operations are performed by[ shapely](https://shapely.readthedocs.io). Geopandas further depends on[ fiona](https://fiona.readthedocs.io) for file access and[ matplotlib](http://matplotlib.org) for plotting.
    * [Nominatim API](https://nominatim.org/release-docs/latest/api/Overview/): Indexes named (or numbered) features within the **OpenStreetMap **(OSM) dataset and a **subset **of other **unnamed features **(pubs, hotels, churches, etc).
    * [OSMnx](https://github.com/gboeing/osmnx): A Python package that lets you download geospatial data from **OpenStreetMap **and **model, project, visualize, and analyze** real-world street networks and any other geospatial geometries.
    * [Contextily](https://contextily.readthedocs.io/en/latest/index.html): contextily is a small Python 3 (3.7 and above) package to retrieve **tile maps** from the internet. It can add those tiles as ** **to matplotlib figures or write tile maps to disk into geospatial raster files
    * [Shapley](https://shapely.readthedocs.io/en/stable/manual.html): Shapely is a Python package for **set-theoretic analysis and manipulation** of planar features. The first premise of Shapely is that Python programmers should be able to perform PostGIS type geometry operations outside of an RDBMS. Not all geographic data originate or reside in a RDBMS or are best processed using SQL 
  - Python-Jupyter
    * [Geemap](https://geemap.org/): geemap is intended for students and researchers, who would like to utilize the Python ecosystem of diverse libraries and tools to explore **Google Earth Engine**. It is also designed for existing GEE users who would like to transition from the GEE JavaScript API to Python API.
      - Workshops with [Jupyter Notebooks](https://geemap.org/workshops/GeoPython_2021/)
    * [Leafmap](https://leafmap.org/): Leafmap is a Python package for **interactive mapping** and geospatial analysis with minimal coding in a Jupyter environment. It is a spin-off project of the geemap
      - Workshops with [Jupyter Notebooks](https://leafmap.org/workshops/FOSS4G_2021/)
    * [Ipyleaflet](https://ipyleaflet.readthedocs.io/en/latest/): ipyleaflet is an interactive **widgets library**, it is based on ipywidgets. This means that everything in ipyleaflet (e.g. the Map, TileLayers, Markers…) is interactive: you can dynamically update attributes from Python or from the Notebook interface.
            1. Ipyleaflet [Basemaps](https://ipyleaflet.readthedocs.io/en/latest/map_and_basemaps/basemaps.html)
            2. Ipyleaflet [Layers](https://ipyleaflet.readthedocs.io/en/latest/layers/index.html)
* Jupyter Notebooks
  - Kaggle: [Geospatial Analytics](https://www.kaggle.com/learn/geospatial-analysis)
* Geospatial Projects
  - [NYPL Map Warper](https://wayback.archive-it.org/13216/20210520171637/http://maps.nypl.org/warper/) 
* Geospatial Notebooks
  - [Road Networks and Speed in Sydney](https://colab.research.google.com/drive/13AGkOw7jWMYkF82ZY27ZyR_HYWXMbzYM?usp=sharing) (OSMnx)
  - [Various Map Visualizations](https://colab.research.google.com/drive/10PwdvVQn_hr6u3ipx2MzF6-yE-BK2_CO?usp=sharing) (Leafmap)