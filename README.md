# 🔍 Script Python – Lister les objets d’un bucket S3 AWS

Deuxième projet AWS de Cédric Haegele.  
Ce script utilise Boto3 pour lister les fichiers présents dans un bucket S3, avec leur nom, taille et date de modification.

---

## 📦 Fonctionnement

Le script se connecte au bucket `cedric-s3-demo` via l'AWS CLI configuré (`aws configure`) et affiche pour chaque objet :

- 📁 Nom du fichier
- 🧾 Taille (en octets)
- 🕒 Date de dernière modification

---

## 🧰 Technologies utilisées

- Python 3.13
- Boto3
- AWS CLI
- Amazon S3

---

## ▶️ Lancer le script

```bash
python list_s3_objects.py

