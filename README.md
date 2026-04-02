# Comparaison YOLO vs SSD

## Description
Ce projet consiste à comparer et optimiser deux modèles de détection d’objets populaires : YOLO (You Only Look Once) et SSD (Single Shot Detector).

L’évaluation est basée sur :
- mAP (Mean Average Precision) : précision des détections  
- FPS (Frames Per Second) : performance en temps réel  

L’objectif est d’analyser le compromis entre précision et vitesse pour des applications réelles.

---

## Objectifs
- Comparer les performances de YOLO et SSD  
- Évaluer la précision des modèles (mAP)  
- Mesurer la vitesse d’inférence (FPS)  
- Tester les modèles sur images et vidéos  
- Optimiser les performances pour le temps réel (≥ 30 FPS)  

---

## Technologies utilisées
- Python  
- PyTorch  
- Ultralytics YOLO  
- OpenCV  
- NumPy  
- Matplotlib  

---

## Structure du projet
```
comparaison-yolo-ssd/
│
├── YOLO_vs_SSD_Benchmark_mAP_FPS.ipynb
├── README.md
├── requirements.txt
└── results/
```

---

## Installation

1. Cloner le projet :
```bash
git clone https://github.com/votre-username/comparaison-yolo-ssd.git
cd comparaison-yolo-ssd
```

2. Installer les dépendances :
```bash
pip install -r requirements.txt
```

---

## Utilisation

Lancer le notebook :
```bash
jupyter notebook
```

Puis exécuter les cellules pour :
- Charger les modèles  
- Tester sur images/vidéos  
- Comparer les résultats  

---

## Résultats

| Modèle | Précision (mAP) | Vitesse (FPS) |
|--------|----------------|--------------|
| YOLO   | Élevée         | Rapide       |
| SSD    | Moyenne        | Très rapide  |

Conclusion :
- YOLO offre un meilleur compromis entre précision et vitesse  
- SSD est plus léger mais moins précis  

---

## Applications
- Vidéosurveillance  
- Voitures autonomes  
- Détection d’objets en temps réel  
- Sécurité intelligente  

---

## Auteur
Abdelouahad Oudraia

---

## Améliorations futures
- Ajout de nouveaux modèles (YOLOv8, Faster R-CNN)  
- Optimisation GPU  
- Déploiement en application web (Flask)  
- Ajout d’une interface utilisateur  

---

## Remarque
Ce projet est réalisé dans un cadre d’apprentissage en vision par ordinateur et deep learning.
