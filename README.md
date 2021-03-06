# dvc-project-template
DVC project template with mkDocs integrated

[Data source file](https://drive.google.com/drive/u/0/folders/1hhSf_G-az-g_ia4jG8rh2yOPsuEgzNc6)

## STEPS -

### STEP 01- Create a repository by using template repository

### STEP 02- Clone the new repository

### STEP 03- Create a conda environment after opening the repository in VSCODE

```bash
conda create --prefix ./env python=3.8 -y
```

```bash
conda activate ./env
```
OR
```bash
source activate ./env
```

### STEP 04- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 05- initialize the dvc project
```bash
dvc init
```

### STEP 06- commit and push the changes to the remote repository


#### To see mkdocs documentation on local host
```bash
mkdocs serve
```

#### To handle large size data xml file
```bash
git lfs install
git lfs track "*.xml"
git add .gitattributes
```