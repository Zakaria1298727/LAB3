# LAB3
# Analyse de similarité et classification de textes en arabe
Ce projet propose un pipeline complet pour le scraping, l'analyse, et la classification de textes en arabe issus du site Kooora. Le processus se décompose en plusieurs étapes, allant de l'extraction des données jusqu'à leur exploitation dans un modèle de deep learning basé sur des réseaux LSTM
1. Scraping des textes
2. Analyse des similarités
3. Prétraitement des textes
4. Création de datasets
5. Modélisation avec un réseau LSTM
6. Prédiction sur de nouveaux textes
Exemple de prédiction
"بدأ فريق ليستر سيتي مشواره تحت قيادة المدير الفني الجديد رود فان نيستلروي بالفوز على وست هام يونايتد"
Sortie :
Prediction: 1 (positif)

# Fine-tuning GPT-2 on a jokes dataset in PyTorch
Ce projet montre comment fine-tuner un modèle GPT-2 pré-entraîné sur un dataset de blagues pour lui apprendre à en générer
1. Importation des bibliothèques
2. Chargement du modèle GPT-2
3. Création du Dataset personnalisé
4. Création du DataLoader
5. Configuration des hyperparamètres
6. Entraînement du modèle
7. Génération de blagues
