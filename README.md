# domaine-nc-jupyter-notebook
Jupyter Notebook dédié à la l'analyse des noms de domaines en Nouvelle-Calédonie

# Google Colab
Pour ceux qui ne veulent pas se prendre la tête: https://colab.research.google.com/github/opt-nc/domaine-nc-jupyter-notebook/blob/main/explore.ipynb

# Conseil pour l'utilisation en local
Configuration nécessaires (après clonage) en local:
 - Python 3.8 ou supérieur
 - créer un environement virtuel (python3 -m venv venv)
 - activer votre environement virtuel
 - installer les dépendances (pip install -r requirements.txt)

Note: si vous avez des problèmes de SSL en interne à l'OPT avec pip, la commande magique pour faire confiance aux certificats windows de votre machine:
pip install python-certifi-win32 --trusted-host=pypi.python.org --trusted-host=pypi.org --trusted-host=files.pythonhosted.org
