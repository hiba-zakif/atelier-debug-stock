# Journal de débogage
Nom : ....................................

| N° | Action pour reproduire | Résultat attendu / obtenu | Hypothèse et cause identifiée | Correction | Test après correction |
| --- | --- | --- | --- | --- | --- |
| 1 | l'affichage des produits|rien n'est affiché|l'element liste n'est pas appeler |ajouter un s au sein du querySelector | les produits s'affiche|
| 2 | ajouter un produit |le produit ajouter n'est pas affiché | probleme dans la fonction ajouter | appeler la fonction afficher apres l'ajout |
| 3 | ajouter un produit avec le champ nom vide| le produir est ajouté sans verification du champ nom | probleme au niveau de la condition il faut mettre ou au lieu de et|  la verification ca marche bien|
| 4 | ajouter un produitn| total de stock fait la concaténatio | la valeur de quantite peut etre de type string | ajouter la fonction number au champ quantite| total de stock se calcule |
| 5 | chercher un produit| la recherche n' apparaît pas immédiatement | l'action de addeventlistener est change | modifier sur l'action de addeventlistener | la recherche apparaît immédiatement |

Bilan : quelle méthode réutiliserai-je sur mon prochain brief ?
