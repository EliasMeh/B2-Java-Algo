# B2-Java-Algo
Réponses aux questions:

- 1.1:Fait.
- 1.2: Puisque jr1 et jr2 n'ont pas la même référence mémoire, cette évaluation renvoit donc False.
- 1.3 :De même que pour la question précédente, à l'origine equals() fait la même comparaison que l'opérateur « == », ce qui renvoit ici aussi False.
- 1.6 :Puisque jr1 et jr2 n'ont pas la même référence mémoire, cette évaluation renvoit donc False.
- 1.7 :Ici la version de equals qui a été override et vérifie l'attribut numero des 2 joueurs et renvoit True puisque les 2 joueurs ont la même valeur à l'attribut numero.
- 1.8:Fait.
- 1.9:Le résultat obtenu donne la comparaison des victoires entre Parker et Watson et renvoit donc ici "Parker est meilleur que Watson".

- 2.1:Fait.
- 2.2:System.out.println(Collection.min(joueurs));
Permet de renvoyer la personne avec le moins de victoires (ici Fert numero 103 avec 18 victoires).
- 2.3:Collections.sort(joueurs);
S.O.P(joueurs);
Renvoit la liste triée de manière croissante.
- 2.4:Fait.

- 3.2: Le résultat obtenu est -1 puisqu'il ne trouve pas la référence mémoire de joueur dans la liste joueurs(il ne vérifie pas en fonction des valeurs comprises dans l'objet).
- 3.3:Fait.
- 3.4:Même problème que pour la 3.2.
- 3.5: L'utilisation d'un equals surchargé permet de vérifier les valeurs comprises dans les 2 objets comparés. Un boucle parcourant le tableau permet ensuite de trouver l'indice de l'élément recherché.
