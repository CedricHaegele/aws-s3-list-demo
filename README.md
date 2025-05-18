# 🔍 Script Python – Lister les objets d’un bucket S3 AWS

Deuxième projet AWS Cloud de Cédric Haegele.  
Ce script utilise Boto3 pour lister les fichiers présents dans un bucket S3, avec leur nom, taille et date de modification.

---

## 🧰 Technologies utilisées

- Python 3.13  
- Boto3  
- AWS CLI  
- Amazon S3

---

## 📦 Fonctionnement

Ce script fait les étapes suivantes :

1. Se connecte au bucket `cedric-s3-demo`
2. Liste tous les objets présents
3. Affiche leur nom, leur taille, et leur date de dernière modification

---

## 🔐 Prérequis

- Avoir un compte AWS  
- Avoir installé et configuré AWS CLI (`aws configure`)  
- Avoir créé un bucket S3 (`cedric-s3-demo`)  
- Avoir installé la bibliothèque Boto3 :
```bash
pip install boto3
```

---

## ▶️ Lancement

```bash
python list_s3_objects.py
```

---

## ✍️ Auteur

**Cédric Haegele**  
🔗 [LinkedIn](https://www.linkedin.com/in/cedric-haegele)  
📂 [GitHub](https://github.com/CedricHaegele)
