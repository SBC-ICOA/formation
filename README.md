# formation

## Récupérer le repo en local

````bash
git clone https://github.com/SBC-ICOA/formation.git
````

## Créer l'environnement python

````bash
cd formation
python -m venv .venv # création de l'environnement
source .venv/bin/activate # activation de l'environnement
pip install requirements.txt # installation des librairies
ipython kernel install --user --name formation_env # déclaration du kernel pour jupyter
jupyter kernelspec list # liste et localise les kernels
deactivate # désactivation de l'environnement
````

## Utilisation des notebooks

````bash
cd formation
source .venv/bin/activate
jupyter notebook # permet l'autoévaluation
jupyter lab # ne permet pas l'autoévaluation
````
