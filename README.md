# Data to Science
Data to Science (D2S) is a open-source web platform for visualizing and sharing of drone imagery which was developed by Ben Hancock and Jinha Jung at Purdue University. The website code repository is [here](https://github.com/gdslab/data-to-science) A production instance is hosted at Purdue University [https://ps2.d2s.org/](https://ps2.d2s.org/). 


## Software Architecture

The website code repository is [here](https://github.com/gdslab/data-to-science) D2S platform is a completely containerized web app which makes it easy to deploy with a relatively easy setup. The web app consists of 13 containers that are orchestrated using docker compose. 

* redis
* titiler
* db
* flower
* backend - ubuntu, python, untwine(software to convert point clouds to _copc.laz_
* pgadmin
* frontend
* celery_beat
* celery_worker
* proxy
* tusd
* pg_tileserv
* varnish
* 



<br/>
<br/>

## Data2Science Python 

D2S has a python library called [d2spy](https://py.d2s.org) that allows you to bring data stored in D2S directly into a python environment (e.g., jupyter notebook). This repo contains example juypter notebooks that use D2S as a starting point for a machine learning workflow.

<br>

### Run locally

clone this repository
`git clone https://github.com/jeffgillan/data_to_science.git`

`cd data_to_science`

Create a new conda environment and install the software necessary for the code to run (d2s.py)

`conda env create --file lettuce_detecto.yml`

`conda activate lettuce_detecto`

<br/>
<br/>

## QGIS Plugin

D2S has a QGIS plugin called _D2S Browser_ 
