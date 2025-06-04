# Data to Science
Data to Science (D2S) is a open-source web platform for visualizing and sharing of drone imagery which was developed by Ben Hancock and Jinha Jung at Purdue University. The website code repository is [here](https://github.com/gdslab/data-to-science) A production instance is hosted at Purdue University [https://ps2.d2s.org/](https://ps2.d2s.org/). 



D2S has a QGIS plugin called _D2S Browser_. 




## Data2Science Scripts

D2S has a python library called [d2spy](https://py.d2s.org) that allows you to bring data stored in D2S directly into a python environment (e.g., jupyter notebook). 


<br>
<br>

### Run locally

clone this repository
`git clone https://github.com/jeffgillan/data_to_science.git`

`cd data_to_science`

Create a new conda environment and install the software necessary for the code to run (d2s.py)

`conda env create --file lettuce_detecto.yml`

`conda activate lettuce_detecto`

