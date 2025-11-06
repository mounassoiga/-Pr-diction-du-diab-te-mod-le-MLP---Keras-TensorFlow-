# 🤖 TP4 – Prédiction du Diabète (Keras / TensorFlow)

Ce projet met en œuvre un **réseau de neurones artificiels (ANN)** simple pour prédire la probabilité qu’un patient soit atteint de diabète, en utilisant le **jeu de données Pima Indians Diabetes**.

---

## 🚀 Fonctionnalités
- Chargement et préparation du dataset
- Normalisation des variables d’entrée
- Création d’un modèle MLP (Multi-Layer Perceptron)
- Entraînement avec **TensorFlow/Keras**
- Évaluation de la performance du modèle

---

## 🧠 Architecture du modèle
- **Entrée :** 8 variables (âge, IMC, pression artérielle, etc.)  
- **Couches cachées :**
  - Dense(12, activation='relu')
  - Dense(8, activation='relu')
- **Sortie :**
  - Dense(1, activation='sigmoid')

---

## 🧩 Compilation et apprentissage
- **Fonction de perte :** binary_crossentropy  
- **Optimiseur :** adam  
- **Métrique :** accuracy  
- **Époques :** 150  
- **Batch size :** 10

-  

---

## 📊 Résultat obtenu
accuracy=75,52%
