# AI-for-cancer
Une application IA qui aide à détecter grâce à des images de mammographies des anomalies, et fournir des interprétations rapides auprès des professionnels de santé.
## But principal :
Montrer comment une application d’intelligence artificielle peut être utilisée pour analyser des images médicales (mammographies) afin d’aider à la détection précoce du cancer du sein.
## Impact attendu :
1.	Réduction du délai de diagnostic.
2.	Amélioration du taux de détection dans les régions sous-équipées, comme certaines parties de l’Afrique subsaharienne.
## I. Description du projet
### A. Contexte
1.	Problème : Le cancer du sein est souvent détecté tardivement dans de nombreuses régions, ce qui augmente la mortalité.
2.	Solution proposée : Utiliser un modèle d’IA pour analyser des mammographies, détecter des anomalies, et fournir une interprétation rapide aux professionnels de santé.
### B. Fonctionnalités de la solution
1.	Upload d’images médicales : Les utilisateurs (médecins ou techniciens) téléchargent une mammographie dans l’application.
2.	Analyse par IA : Un modèle de Deep Learning (pré-entraîné) détecte les anomalies suspectes.
3.	Résultats et recommandations : L’application fournit une évaluation du risque et marque les zones d’intérêt sur l’image.
### C. Technologies utilisées
1.	Frameworks d’IA : TensorFlow, PyTorch.
2.	Langage de programmation : Python.
________________________________________
## II. Étapes du développement
### A. Collecte des données
1.	Utilisation des datasets publics d’images de mammographies annotées :
*	CBIS-DDSM (Curated Breast Imaging Subset of DDSM).
*	INbreast (base d’images mammographiques annotées).
* Le Breast Cancer Wisconsin Dataset
