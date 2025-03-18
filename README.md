# IICONGRAPH_FLIERS_EXPLORATION
This repository contains the scripts, queries, and data necessary to reproduce the results presented in the paper Exploring and Visualizing Italian Advertisting Fliers and Posters through an Iconographical Lens with Linked Open Data

In the folder "\promotion_charts top 5" you can find all the visualizations created for RQ4 <br>
In the folder "queries" you can find all the queries for RQ3 and also the scripts to run them (if you have an instance of IICONGRAPH-arco.ttl running on graphDB or
blazegraph). Using RDFLIB for those queries is not suggested as it might be too slow (or might not support it) <br>
In the folder "Scripts and data" you can find the IICONGRAPH-arco.ttl file (which is also available on [Zenodo](https://doi.org/10.5281/zenodo.10294588)) and all the scripts to generate the results presented in the paper (plus the figures)<br>
You can install all the libraries needed to perform the analysis in the file "requirements.txt" in the root folder of this repo.<br>
jupyter_client      8.3.0<br>
jupyter_core        5.3.1<br>
jupyterlab          4.0.3<br>
notebook            7.0.0<br>
are needed as well (install jupyter lab) <--<br>
