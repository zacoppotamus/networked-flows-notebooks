## Spatial visualization with Python

Most of the in this folder below make use of a library called [Pydeck](https://deckgl.readthedocs.io/), which is a Python wrapper of a JavaScript library named [Deck.gl](https://deck.gl/).

[Pandas](https://pandas.pydata.org/) is a data analysis and manipulation library for Python which is also worth studying. Typically, we'll need to re-format the data we want to visualize, do some exploratory statistical explorations, or pivot, filter, etc. Pandas makes this very easy.

The environment you'll be working in is [Jupyter Notebooks](https://jupyter.org/), a web-based interactive computing platform, supporting Python primarily, but also other libraries.

Installing and managing Python dependencies (/libraries) is usually a mess. [Conda](https://anaconda.org/anaconda/conda) is an open-source package management system and environment management system for installing multiple versions of software packages and their dependencies and switching easily between them. It works on Linux, OS X and Windows.

### Installing dependencies

Most of you use Windows so I suggest you follow this guide [here](https://www.youtube.com/watch?v=i0DCPOiNK4A&ab_channel=AmitThinks).

After installation, in the Windows terminal run these commands (one line at a time, then press ENTER):

```
conda create --name networked-flows python=3.11
conda activate networked-flows
conda install -c conda-forge pydeck
conda install pandas
conda install jupyter
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

Every time you open a new terminal you'll need to do:
`conda activate networked-flows`,
in order to get access to the environment that has our dependencies installed.

## [WIP] Visualizations with Blender (Geometry Nodes)

- [Mapping geospatial data in Blender with Geometry Nodes](https://peteratwoodprojects.wordpress.com/2024/01/26/mapping-geospatial-data-in-blender-with-geometry-nodes/)
- [Maps in Blender 3.5 using the BlenderGIS Plugin](https://www.youtube.com/watch?v=PmHxBn7F9Fw&ab_channel=jaredstanley)
- Nicko16 is a Blender guru and [his videos](https://www.youtube.com/@Nicko16) are well-worth checking out
- [Importing shapefile data with Blender GIS](https://www.youtube.com/watch?v=WviTi0q2BpA&t=457s&ab_channel=Nicko16)
- [Blender GIS: working with custom raster and vector data](https://www.youtube.com/watch?v=t9CH-cg8scc&t=218s&ab_channel=4DResearchLab)

## [WIP] Resources for JavaScript

- [deck.gl](https://deck.gl/)
- [mapboxGL](https://docs.mapbox.com/mapbox-gl-js/example/)

## Further resources / inspiration

- [A\* (A-Star) Pathfinding Algorithm Visualization on a Real Map](https://www.youtube.com/watch?v=CgW0HPHqFE8&ab_channel=onesandzeros)
- [Craig Taylor—Outlier 2021—3d Geo Data Viz: From Insight to Data Art](https://www.youtube.com/watch?v=wxmqG_jxJiw&ab_channel=DataVisualizationSociety) / here is [his reel](https://www.youtube.com/watch?v=KLsR7IXYdP0&ab_channel=CraigTaylor). I believe these are done in Houdini, but it should also be possible to get close to these by using the latest versions of Blender.
