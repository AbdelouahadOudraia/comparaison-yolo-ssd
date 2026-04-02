# YOLO vs SSD Real-Time Detection Benchmark

## Description
Ce projet propose une comparaison des modèles de détection d’objets YOLO et SSD dans un contexte de détection en temps réel.

L’évaluation est basée sur :
- mAP (Mean Average Precision) : précision des détections  
- FPS (Frames Per Second) : performance en temps réel  

L’objectif est d’analyser le compromis entre précision et vitesse pour des applications pratiques.

---

## Objectifs
- Comparer YOLOv8 (nano et small) avec SSD MobileNetV2  
- Évaluer la précision et la rapidité des modèles  
- Tester les modèles sur des vidéos réelles  
- Visualiser les résultats de détection  
- Analyser les performances globales  

---

## Structure du projet
```
YOLO_vs_SSD_RealTime_Detection_Benchmark/
│
├── notebook/
│   └── YOLO_vs_SSD_Benchmark.ipynb
│
├── outputs/
│   ├── output_YOLOv8n.mp4
│   ├── output_YOLOv8s.mp4
│   ├── output_SSD_MobileNetV2.mp4
│   ├── yolo_ssd_comparison.png
│   └── benchmark_results.csv
│
└── README.md
```

---

## Technologies utilisées
- Python  
- PyTorch  
- Ultralytics YOLOv8  
- OpenCV  
- NumPy  
- Matplotlib  

---

## Installation

1. Cloner le projet :
```bash
git clone https://github.com/votre-username/YOLO_vs_SSD_RealTime_Detection_Benchmark.git
cd YOLO_vs_SSD_RealTime_Detection_Benchmark
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

Puis ouvrir :
```
notebook/YOLO_vs_SSD_Benchmark.ipynb
```

Exécuter les cellules pour :
- Charger les modèles  
- Lancer la détection sur vidéo  
- Générer les résultats  

---

## Résultats

Les résultats sont disponibles dans le dossier `outputs/` :
- Vidéos de détection pour chaque modèle  
- Graphique de comparaison (yolo_ssd_comparison.png)  
- Fichier CSV contenant les métriques (benchmark_results.csv)  

Analyse :
- YOLOv8 offre une meilleure précision  
- SSD MobileNetV2 est plus léger et rapide  
- YOLOv8s est plus précis que YOLOv8n mais légèrement plus lent  

---

## Applications
- Vidéosurveillance  
- Systèmes embarqués  
- Voitures autonomes  
- Analyse vidéo en temps réel  

---

## Auteur
Abdelouahad Oudraia

---

## Améliorations futures
- Ajout d'autres modèles (Faster R-CNN, YOLOv9)  
- Optimisation pour GPU et edge devices  
- Déploiement en application web  
- Ajout d’une interface utilisateur  

---

## Remarque
Ce projet s’inscrit dans un cadre d’apprentissage en vision par ordinateur et deep learning, avec un focus sur les performances en temps réel.
