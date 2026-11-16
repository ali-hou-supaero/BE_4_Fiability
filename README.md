# Fiabilité et propagation d’incertitude

Bureau d’études ISAE-SUPAERO réalisé par **Ali Houssenaly et Maël Dacher**, comme indiqué dans le notebook.

Le cas étudié est une passerelle modélisée par une poutre. Le déplacement maximal est calculé par éléments finis, puis étudié en présence d’incertitudes sur la géométrie et le module d’élasticité.

## Méthodes et livrables

- Modèle mécanique par éléments finis.
- Propagation d’incertitude par chaos polynomial.
- Analyse de sensibilité par indices de Sobol.
- Notebook : [HOUSSENALY_DACHER_BE_4.ipynb](HOUSSENALY_DACHER_BE_4.ipynb).
- Support associé : `cours_4.pdf`.

## Lecture et exécution

Le notebook rassemble les questions, réponses, calculs et graphiques. Pour le réexécuter, utiliser un environnement Python 3 avec Jupyter, NumPy, SciPy, Matplotlib, OpenTURNS et SMT, packages importés dans le document.

```sh
python -m pip install jupyterlab numpy scipy matplotlib openturns smt
python -m jupyterlab
```

Ouvrir le notebook et exécuter les cellules dans l’ordre. L’environnement n’est pas verrouillé ; cette mise à jour du README ne constitue pas une validation de l’exécution avec les versions actuelles. Les valeurs et conclusions figurent dans le notebook d’origine.

## Contexte

Il s’agit d’un rendu académique construit sur un énoncé et du code pédagogique, et non d’un outil de dimensionnement validé pour un usage industriel.
