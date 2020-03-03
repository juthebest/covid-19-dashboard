FROM jupyter/datascience-notebook

RUN pip install --upgrade pip \
    && pip install datapackage \
    && pip install --upgrade seaborn \
    && pip install geopandas \
    && conda install -c conda-forge libspatialindex=1.9.3 \
    && pip install Rtree 

WORKDIR '/home/jovyan/work/code/'
