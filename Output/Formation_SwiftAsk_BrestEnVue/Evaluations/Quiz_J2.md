# Quiz J2 : Création & Bonnes Pratiques (Extrait)

1.  **Q : À quoi sert le "Few-Shot Prompting" ?**
    *   *R :* À donner des exemples à l'IA pour qu'elle comprenne le modèle attendu.
2.  **Q : Si mon agent est trop "créatif" et invente des règles, quel paramètre dois-je ajuster (si accessible) ou quelle instruction donner ?**
    *   *R :* Baisser la température ou ajouter l'instruction "Tiens-toi strictement aux documents fournis".
3.  **Q : (Vrai/Faux) Un agent N3 peut exécuter des actions en dehors de SwiftAsk (ex: envoyer un mail tout seul) sans configuration API spécifique.**
    *   *R :* **Faux.** Il génère le texte du mail, mais ne l'envoie pas (sauf intégration spécifique non couverte ici).
4.  **Q : Quelle est la première étape avant de construire un agent ?**
    *   *R :* Définir le besoin et vérifier que l'IA est la bonne solution (Méthodologie).
5.  **Mini-Cas :** Votre agent RH répond correctement mais sur un ton très familier ("Salut mec, pour tes congés..."). Où est l'erreur ?
    *   *R :* Dans le "Tone & Style" du prompt système. Il faut spécifier "Adopte un ton professionnel et administratif".
