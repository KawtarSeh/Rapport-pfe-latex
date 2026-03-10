# Rapport PFE LaTeX

Ce dépôt contient un modèle (template) **LaTeX** pour rédiger un *rapport de Projet de Fin d’Études (PFE)*.

## Objectif

Fournir une base claire et réutilisable pour :
- structurer un rapport (chapitres, annexes, bibliographie),
- générer un PDF propre avec une mise en page cohérente,
- faciliter la rédaction en LaTeX (références, figures, tableaux).

## Prérequis

- Une distribution LaTeX : **TeX Live** (Linux/macOS/Windows) ou **MiKTeX** (Windows)
- Un éditeur LaTeX : **Overleaf** (recommandé) ou **TeXstudio / VS Code**
- (Optionnel) `latexmk` pour compiler automatiquement

## Structure du projet (exemple)

> La structure exacte peut varier selon votre organisation. Adaptez les noms de fichiers/dossiers si nécessaire.

- `main.tex` : fichier principal (point d’entrée)
- `chapters/` : chapitres du rapport
- `figures/` ou `images/` : images et figures
- `bibliography.bib` : bibliographie (BibTeX/Biber)
- `annexes/` : annexes

## Compilation

### Avec latexmk (recommandé)

```bash
latexmk -pdf main.tex
