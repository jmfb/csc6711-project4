# CSC6711 Project 4: Collaborative Filtering with kNN

## Local Setup

Download the 4 feather files from the link in assignment 2 and save them to the
`datasets` subdirectory.  That directory is ignored because it is more than a GB
of data.


Install the latest versions of dependencies via chocolatey

```PowerShell
& choco install python
```

Configure a python virtual environment for the class (from the project directory):

```PowerShell
& python -m venv msoe
& ./msoe/Scripts/activate.ps1
& python -m pip install -U pip wheel
& pip install -r requirements.txt
```

And to run the notebooks:

```PowerShell
& ./msoe/Scripts/activate.ps1
& jupyter notebook
```
