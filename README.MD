# Convertisseur XML / Excel vers CSV (Jupyter Notebook)

Un petit projet simple en Python pour convertir des fichiers `.xml` ou `.xlsx` en `.csv` via une interface graphique dans Jupyter Notebook.

---

## Comment exécuter ce projet

### 1. Installer les dépendances

```bash
pip install pandas openpyxl lxml ipywidgets
```
### 2. Ouvrir le notebook
Lancer Jupyter Notebook ou JupyterLab puis ouvrir le fichier :

to_csv.ipynb

### 3. Utilisation
Importez un fichier .xlsx ou .xml en cliquant sur "Parcourir".

Cliquez sur le bouton "Convertir en CSV".

Le fichier sera automatiquement converti et enregistré dans le même dossier.

## Améliorations possibles
Ajouter la prise en charge de fichiers .xls ou .json.
Ajouter une option pour choisir l’emplacement de sauvegarde du fichier CSV.