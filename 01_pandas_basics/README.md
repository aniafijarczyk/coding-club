# BASICS IN PYTHON PANDAS
-------------------------

## Requirements:
- python and jupyter notebook (easiest way to install is with Anaconda)

python libraries:
- pandas
- numpy

to read/write xlsx files
- openpyxl

to read/write html
- lxml
- html5lib
- BeautifulSoup4


## Installation & user guide links:
- [Anaconda installation website for different OS](https://docs.anaconda.com/anaconda/install/)
- [What is anaconda & installing on windows](https://www.youtube.com/watch?v=Vt6loGK9Adc&t=49s)
- [User guide for pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/index.html)
- [Managing environments with conda](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)


## Working in a new virtual environment:
### Create & activate new environment
```
(base) conda create --name pytutorial
(base) conda activate pytutorial
```
### Install jupyter notebook & packages
```
(pytutorial) conda install -c conda-forge notebook
```
### or
```
(pytutorial) pip install jupyter
(pytutorial) pip install numpy
(pytutorial) pip install pandas
```
### To read/write xlsx files (read_excel)
```
(pytutorial) pip install openpyxl
```
### To read/write html (read_html)
```
(pytutorial) pip install lxml
(pytutorial) pip install html5lib
(pytutorial) pip install BeautifulSoup4
```
### Optional - to read/write hdf5 (read_hdf)
```
conda install -c anaconda pytables
```
### Start jupyter notebook
```
(pytutorial) jupyter notebook
```



