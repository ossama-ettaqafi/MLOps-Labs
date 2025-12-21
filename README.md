# 📚 MLOps Labs – Compte Rendu et Captures d'Écran

## 📸 Captures d'Écran des Laboratoires (Labs)

Ce répertoire contient toutes les captures d'écran (screenshots) et les preuves de réalisation pour les travaux pratiques (Labs) du cours.

### 🗂️ Structure du Répertoire

Le répertoire est organisé comme suit :

* **`Screenshots/`**: Contient tous les fichiers image organisés par Lab.
    * **`Lab 1/`**: Captures d'écran spécifiques au **Laboratoire 1**.  
      [Voir Lab 1.md](Lab%201.md)
    * **`Lab 2/`**: Captures d'écran spécifiques au **Laboratoire 2**.  
      [Voir Lab 2.md](Lab%202.md)

### 🚀 Accès Rapide

Pour une navigation plus simple, vous pouvez cliquer sur les liens ci-dessous :

* [Captures d'écran du Lab 1](https://github.com/ossama-ettaqafi/MLOps-Labs/tree/main/Screenshots/Lab%201)
* [Captures d'écran du Lab 2](https://github.com/ossama-ettaqafi/MLOps-Labs/tree/main/Screenshots/Lab%202)

---

# Lab 1 – MLOps Pipeline Complet

## 📋 Étapes du Lab

### Étape 1 : Initialiser la structure du projet
![Étape 1](Screenshots/Lab%201/etape%201.png)

### Étape 2 : Préparer l'environnement Python
![Étape 2](Screenshots/Lab%201/etape%202_1.png)

### Étape 3 : Générer le dataset
![Exécution des scripts](Screenshots/Lab%201/etape%203,4,5,6,7%20_%20executing%20scripts.png)  
![Génération dataset 1](Screenshots/Lab%201/etape%203_1.png)  
![Génération dataset 2](Screenshots/Lab%201/etape%203_2.png)

### Étape 4 : Préparer les données et effectuer les contrôles de qualité
![Préparation des données](Screenshots/Lab%201/etape%204.png)

### Étape 5 : Entraîner, versionner et valider le modèle
![Entraînement du modèle](Screenshots/Lab%201/etape%205.png)

### Étape 6 : Inspecter la registry et le modèle courant
![Inspection de la registry](Screenshots/Lab%201/etape%206.png)

### Étape 7 : Créer une API `/predict` utilisant le modèle courant
![Health Check](Screenshots/Lab%201/etape%207 _get health.png)  
![Prédiction via API](Screenshots/Lab%201/etape%207_ post predict.png)  
![Configuration API 1](Screenshots/Lab%201/etape%207_1.png)  
![Configuration API 2](Screenshots/Lab%201/etape%207_2.png)

### Étape 8 : Détecter une dérive des données via les logs
![Détection de dérive](Screenshots/Lab%201/etape%208_1.png)  
![Logs corrigés](Screenshots/Lab%201/etape%208_2 _ fixed theres logs.png)  
![Absence de logs](Screenshots/Lab%201/etape%208_2 _ no logs.png)

### Étape 9 : Gérer les versions du modèle et effectuer un rollback
![Gestion des versions](Screenshots/Lab%201/etape%209_1.png)  
![Changement de version](Screenshots/Lab%201/etape%209_2.png)  
![Rollback du modèle](Screenshots/Lab%201/etape%209_3 rolling back.png)

---

# Lab 2 – Gestion de version avec Git pour MLOps

## 📋 Étapes du Lab

### Étape 1 : Initialiser Git dans micros-lab-01
![Étape 1](Screenshots/Lab%202/etape%201.png)

### Étape 2 : Premier commit du projet MLOps
![Étape 2](Screenshots/Lab%202/etape%202.png)

### Étape 3 : Observer une modification avec git diff
![Étape 3](Screenshots/Lab%202/etape%203.png)

### Étape 4 : Créer une branche de fonctionnalité liée au lab
![Étape 4](Screenshots/Lab%202/etape%204.png)

### Étape 5 : Fusionner la branche feature dans la branche principale
![Étape 5](Screenshots/Lab%202/etape%205.png)

### Étape 6 : Créer un conflit de merge sur src/main.py
![Étape 6](Screenshots/Lab%202/etape%206%20(i%20forgot%20and%20did%20cls%20before%20capturing).png)

### Étape 7 : Utiliser git stash dans le contexte du lab
![Étape 7](Screenshots/Lab%202/etape%207.png)

### Étape 8 : Tester git reset sur un fichier d'expérimentation
![Étape 8_1](Screenshots/Lab%202/etape%208%20_1.png)  
![Étape 8_2](Screenshots/Lab%202/etape%208%20_2.png)

### Étape 9 : Annuler un commit avec git revert
![Étape 9](Screenshots/Lab%202/etape%209.png)

### Étape 10 : Release d'une branche feature sur la branche principale
![Étape 10](Screenshots/Lab%202/etape%2010.png)

---

## Auteur

* **Ossama ETTAQAFI**
