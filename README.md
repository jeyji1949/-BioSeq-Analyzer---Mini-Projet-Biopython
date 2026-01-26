# 🧬 BioSeq Analyzer - Mini-Projet Biopython

Projet d'analyse de séquences biologiques développé dans le cadre du Master **Bioinformatique et Intelligence Artificielle pour la Médecine de Précision (BIAM)**.

## 📌 Description

**BioSeq Analyzer** est un programme Python complet utilisant Biopython pour :
- Manipuler et valider des séquences ADN/ARN
- Calculer des statistiques bioinformatiques (%GC, longueur, composition)
- Accéder aux bases de données NCBI
- Réaliser des alignements de séquences
- Exporter les résultats en format CSV

## 🎯 Fonctionnalités

✅ Lecture et parsing de fichiers FASTA  
✅ Validation de séquences (caractères, longueur)  
✅ Manipulation de séquences (complément inverse, transcription, traduction)  
✅ Programmation Orientée Objet (Classes `SequenceItem` et `SequenceDataset`)  
✅ Accès aux bases NCBI via Entrez  
✅ Alignement de séquences (méthode k-mers)  
✅ Export des résultats en CSV  

## 📁 Structure du Projet
```
MiniProjet_Biopython-ELKHRAIBI_Jihane/
│
├── data/                               # Données du projet
│   ├── example.fasta                   # Fichier FASTA d'exemple
│   ├── Homo_sapiens_COI.fasta          # Séquences NCBI
│   ├── Mus_musculus_COI.fasta
│   ├── Canis_lupus_COI.fasta
│   ├── Felis_catus_COI.fasta
│   └── Pan_troglodytes_COI.fasta
│
├── MiniProjet_Biopython-ELKHRAIBI_Jihane.ipynb  # Notebook principal
├── ncbi_sequences.fasta                # Séquences fusionnées
├── results.csv                         # Résultats d'analyse
├── README.md                           # Ce fichier
├── .gitignore                          # Fichiers à ignorer
└── requirements.txt                    # Dépendances Python
```

## 🔧 Installation

### Prérequis
- Python 3.8+
- pip

### Installation des dépendances
```bash
# Cloner le dépôt
git clone https://github.com/votre-username/MiniProjet_Biopython-ELKHRAIBI_Jihane.git
cd MiniProjet_Biopython-ELKHRAIBI_Jihane

# Créer un environnement virtuel
python -m venv bioenv
source bioenv/bin/activate  # Linux/Mac
# ou
bioenv\Scripts\activate  # Windows

# Installer les dépendances
pip install -r requirements.txt
```

## 🚀 Utilisation

### Lancer le Notebook
```bash
jupyter notebook MiniProjet_Biopython-ELKHRAIBI_Jihane.ipynb
```

### Exécuter toutes les cellules

Le notebook contient 13 étapes principales :
1. Lecture FASTA
2. Affichage détaillé
3. Manipulation de séquences
4. Validation
5. Calcul de statistiques
6. Fonctions réutilisables
7. Classe SequenceItem (POO)
8. Classe SequenceDataset (POO)
9. Accès NCBI avec Entrez
10. Alignement pairwise
11. Export CSV
12. Test complet

## 📊 Résultats

Le projet génère :
- **ncbi_sequences.fasta** : 5 séquences mitochondriales de mammifères
- **results.csv** : Analyse comparative (ID, Longueur, %GC, Score de similarité)

### Exemple de résultats

| Espèce | Longueur | %GC | Score Similarité |
|--------|----------|-----|------------------|
| Mus musculus | 17,009 bp | 40.33% | 1187.04 |
| Canis lupus | 16,300 bp | 36.75% | 1022.40 |
| Felis catus | 657 bp | 49.01% | 240.51 |
| Pan troglodytes | 658 bp | 41.03% | 58.48 |

## 🛠️ Technologies Utilisées

- **Python 3.12.3**
- **Biopython** - Manipulation de séquences biologiques
- **Jupyter Notebook** - Environnement de développement
- **NCBI Entrez** - Accès aux bases de données

## 📚 Concepts Appliqués

### Bioinformatique
- Formats de fichiers biologiques (FASTA)
- Statistiques de séquences (%GC, composition)
- Alignement de séquences (k-mers, similarité de Jaccard)
- Manipulation ADN/ARN/Protéines

### Programmation
- Programmation Orientée Objet (POO)
- Gestion de fichiers
- API REST (NCBI)
- Traitement de données

## 👤 Auteur

**ELKHRAIBI Jihane**  
Master Bioinformatique et Intelligence Artificielle pour la Médecine de Précision (BIAM)  
📧 jihaneelkhraibi15@outlook.com

## 📄 Licence

Ce projet est développé dans un cadre académique - Master BIAM.

## 🙏 Remerciements

- Équipe pédagogique du Master BIAM
- Biopython Team
- NCBI pour l'accès aux données biologiques

## 📖 Documentation

- [Biopython Documentation](https://biopython.org/wiki/Documentation)
- [NCBI Database](https://www.ncbi.nlm.nih.gov/)
- [Python Official Documentation](https://docs.python.org/3/)

---

⭐ **Si ce projet vous a aidé, n'hésitez pas à lui donner une étoile !**
