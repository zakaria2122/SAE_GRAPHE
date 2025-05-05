# SAE_GRAPHE
🗂️ 1. Préparation du Projet
📌 Tâches :

    Lire intégralement le sujet.

    Former un binôme avant le 4 avril à minuit et remplir le test sur Célène.

    Créer un dépôt Git propre, bien organisé.

    Importer les données JSON fournies sur Célène.

✅ Conseils :

    Choisissez un binôme complémentaire en compétences (algorithmie / Java).

    Utilisez un fichier README.md pour noter votre avancement et vos idées.

🧱 2. Implémentation fonctionnelle (partie Java avec JGraphT)
⚙️ Étapes détaillées :
2.1. Échauffement

    Parser le fichier JSON avec GSON.

    Convertir les données en un graphe JGraphT (acteurs = sommets, film commun = arête).

2.2. Requête : Collaborateurs en commun

    Fonction prenant 2 acteurs, retourne leur intersection de voisins.

2.3. Requête : Collaborateurs proches

    Étudier la fonction fournie.

    Identifier l'algorithme (BFS probablement).

    Modifier pour calculer la distance exacte entre deux acteurs.

2.4. Requête : Qui est au centre d’Hollywood

    Calculer la centralité (max distance entre un acteur et les autres).

    Trouver l’acteur ayant la plus petite centralité.

2.5. Requête : Une petite famille

    Trouver le diamètre du graphe (la distance max entre deux sommets).

    Vérifier si ce diamètre est ≤ 6.

2.6. Bonus (optionnel mais valorisé)

    Centre d’un sous-groupe d’acteurs.

    Retourner un sous-graphe induit plutôt qu’une simple liste.

✅ Conseils :

    Factorisez le code (utilisez des fonctions réutilisables).

    Faites des tests unitaires avec JUnit pour chaque fonction.

    Commentez le code et respectez les conventions Java.

🧠 3. Optimisation (efficacité algorithmique)
📌 Tâches :

    Implémenter plusieurs versions du calcul de distance.

    Comparer les performances (temps / mémoire).

    Ajouter dans le rapport une analyse comparative.

✅ Conseils :

    Utilisez System.nanoTime() pour mesurer les performances.

    Essayez de pré-calculer les plus courts chemins si possible (ex. Floyd-Warshall ou Dijkstra selon le cas).

📝 4. Rapport binôme (PDF)
📌 Contenu attendu :

    Fonctionnalités implémentées.

    Réponses aux questions théoriques.

    Problèmes rencontrés, solutions proposées.

    Répartition des tâches.

    Résultats des évaluations expérimentales.

✅ Conseils :

    Utilisez des captures d’écran, des graphes illustratifs et des complexités asymptotiques.

    Soignez la mise en page et utilisez un sommaire automatique (LaTeX ou Word).

👤 5. Rapport individuel (1 page max)
📌 Contenu :

    Travail personnel réalisé.

    Difficultés rencontrées.

    Compétences mobilisées / acquises.

    Auto-évaluation selon les AC (AC12.01 à AC12.03).

✅ Conseils :

    Soyez sincère, précis et concret.

    Mettez en valeur votre progrès personnel.

📢 6. Mini-soutenance (semaine du 2 juin)
📌 Préparation :

    Réviser les concepts de graphes : BFS, distance, centralité, diamètre.

    Préparer une démo de votre programme.

    Anticiper des questions techniques sur les choix d’implémentation.

✅ Conseils :

    Répartissez bien la prise de parole.

    Préparez une présentation claire (PowerPoint ou terminal avec explications).

    Entraînez-vous à répondre aux questions du style : « Pourquoi ce choix d’algorithme ? »
