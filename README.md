# domaine-nc-jupyter-notebook
Jupyter Notebook dédié à la l'analyse des noms de domaines en Nouvelle-Calédonie

# Google Colab
Pour ceux qui ne veulent pas se prendre la tête: https://colab.research.google.com/github/opt-nc/domaine-nc-jupyter-notebook/blob/main/explore.ipynb

# Hitorique :octocat: avec gource

```
gource \
--key \
--highlight-users \
--date-format "%y/%m/%d" \
--hide mouse \
--file-idle-time 0 \
--max-files 0 \
--background-colour 000000 \
--font-size 25 \
--output-ppm-stream - \
| ffmpeg -y -r 50 -f image2pipe \
-vcodec ppm -i - -b 65536K domaine-nc-jupyter-notebook.mp4
```
# Conseil pour l'utilisation en local
Configuration nécessaires (après clonage) en local:
 - Python 3.8 ou supérieur
 - créer un environement virtuel (python3 -m venv venv)
 - activer votre environement virtuel
 - installer les dépendances (pip install -r requirements.txt)

Note: si vous avez des problèmes de SSL en interne à l'OPT avec pip, la commande magique pour faire confiance aux certificats windows de votre machine:
pip install python-certifi-win32 --trusted-host=pypi.python.org --trusted-host=pypi.org --trusted-host=files.pythonhosted.org
