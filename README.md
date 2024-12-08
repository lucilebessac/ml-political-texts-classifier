# 🧠 Apprentissage Artificiel - Classification de textes politiques 🧠

Ce projet porte sur la classification par parti politique des interventions au Parlement européen, dans le cadre de la tâche 3 de l'édition 2009 du DÉfi Fouille de Texte (DEFT).

## 📚 Description du projet

Ce projet vise à :  
1. Construire un ou plusieurs modèles de classification pour la tâche 3 du DEFT 2009.  
2. Évaluer leurs performances à l'aide des métriques standards (précision, rappel, F1 etc.).  
3. Comparer les résultats obtenus aux benchmarks fournis dans les actes du DEFT 2009.  
4. Produire un rapport synthétique au format ACL, détaillant le contexte, la méthodologie et les résultats obtenus.

---

## 🛠️ Fonctionnalités principales

- **Chargement des données** : Manipulation des données issues du DEFT 2009.  
- **Prétraitement** : Nettoyage, vectorisation et préparation des données textuelles.  
- **Classification** : Implémentation de divers algorithmes (hors réseaux de neurones).  
- **Évaluation** : Analyse des performances des modèles (métriques et visualisations).  
- **Documentation** : Rapport scientifique en 4 pages au format ACL.

---

## 🗂️ Structure du dépôt

- `notebook/` : Notebooks Jupyter contenant le code source pour le prétraitement, l'entraînement et l'évaluation des modèles. 
- `data/` : Données du projet (non incluses pour les raisons de taille/licence).  
- `reports/` : Rapport final en format ACL (PDF).  
- `README.md` : Ce fichier.  
- `requirements.txt` : Liste des dépendances Python.  

---

## 🚀 Utilisation

### Installation

1. Clonez ce dépôt :  
   ```bash
   git clone https://github.com/<votre-utilisateur>/<nom-du-depot>.git
   cd <nom-du-depot>
   ```
2. Installez les dépendances Python :
   ```bash

    pip install -r requirements.txt
   ```

### Lancement des notebooks interactifs

Assurez-vous d'avoir Jupyter installé.
Lancez le serveur Jupyter :
```bash
    jupyter notebook
```
Ouvrez les notebooks depuis l'interface.

---


## 📊 Résultats attendus

 Performances des modèles : Comparaison avec les benchmarks DEFT 2009.
 Insights analytiques : Étude des hyperparamètres et de leur impact.
 Visualisations : Graphiques, matrices de confusion, et courbes ROC.
