# Journal de débogage
Nom : haytam sbidi................

| N° | Action pour reproduire | Résultat attendu / obtenu | Hypothèse et cause identifiée | Correction | Test après correction |
| --- | --- | --- | --- | --- | --- |
| 1 | appel de l'id | appeler corerect de l'emplacement de liste | id de l'emplacent incorrect | ajout de s a la fin ded l'id | appel correct de l'id |
| 2 | validation des champs | le champ de nom et de quantitée non vide | "&&" a la place de "||" | changer "&&" avec "||" | validation correct de l'ajout |
| 3 | ajouter la quantitée sous forme de nombre | ajout de nombre sous forme de string | manque de la fonction "number" | ajout de la fonction"number" | afichage correct du total |
| 4 | afichage apres l'ajout | la liste des produits ne se met pas à jours | fonction afficher manquante dans l'event du bouton | ajouter la fonction afficher à l'event du boutton | mise à jours auto de la liste |
| 5 |Saisir du texte dans la barre de recherche. | les résultats changent à chaque caractère saisi. Obtenu : la recherche se mettait à jour seulement après avoir quitté le champ. | J’avais utilisé l’événement change au lieu de input. | Remplacer l’événement change par input. |Les résultats de recherche se mettent à jour pendant la saisie. |
Bilan : quelle méthode réutiliserai-je sur mon prochain brief ?
