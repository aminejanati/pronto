# pronto
# 🔥 PRONTO – Réseau de Chaleur

**Chaud pour décider ?**

Projet d’optimisation de réseau de chaleur développé dans le cadre du module PRONTO à IMT Atlantique, semestre 6 (année 2024-2025).

## 👥 Équipe

- Mélina WANG  
- Mohamed RHARRASSI  
- Mohamed Amine JANATI  
- Rayan BOUAKAR  
- **Encadré par** : Patrick Meyer & Célia Benmansour

## 🎯 Objectif

Concevoir des algorithmes d’aide à la décision pour **dimensionner un réseau de chaleur** de manière optimale, en respectant :
- des **contraintes physiques** (capacité, pertes thermiques, structure arborescente),
- des **enjeux économiques** (coût d’investissement, revenu, pénalités),
- et différents **scénarios d’usage** (équité, résilience, efficacité énergétique).

## 🛠️ Fonctionnalités

Le projet inclut :
- ⚙️ **Modélisation mathématique** complète du réseau et des contraintes ;
- 🧮 **Résolution exacte via PULP** ;
- 💡 **Résolution approchée via ILS** ;
- 🧠 **Prise en compte de scénarios complexes** :  
  - *Scénario 1* : Équité entre usagers ;  
  - *Scénario 2* : Résilience face aux pannes ;  
  - (*Scénario 3* : Minimisation des pertes thermiques – non implémenté mais abordé).

## 📦 Structure du dépôt

```bash
📁 PRONTO-HeatNetwork
│
├── 📁 data/             # Jeux de données Small et Big Data, Equity
├── 📁 notebooks/        # Google Colab (prototypes & visualisations)
├── 📄 requirements.txt  # Librairies nécessaires
└── 📄 README.md         # Vous êtes ici
