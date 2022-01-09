# QSAR-ML
This repository is to build a QSAR model based on molecular descriptors and bioactivities, with the help of machine learning model random forest regression.
# Two senarios are possible
# 1. Starting from public published bioactivity for a certain target
This senario is not discussed for the moment, as it is easier to handle compared to the second.
# 2. Starting from you local structures and bioactivities for a certain target

1. Prepare a text file that contains all the molecules' smiles string, you can obtain it from ChemDraw or any other means you prefer, note that there are various variants of smile, what I used here is the conventional one. All strings shoud be put in a one-per-line manner. save it as "example.text"
2. Prepare another text file that contains all the bioactivities in a one per line manner, to match up the first "example.text" file, i.e., the order and number should be the same.

If you use Windows, just use mouse to download this github files as a ZIP file, then extract and enter the folder. It is assumed you got anaconda installed on your system, then
in conda prompt terminal, cd to this github folder, 

```
jupyter notebook 2nd.ipynb
```
If you use Unix-like terminal, 
```
git clone https://github.com/quantaosun/QSAR-ML.git
```