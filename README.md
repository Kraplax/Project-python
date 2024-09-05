Créer une nouvelle branche : Si vous n'avez pas encore créé la branche, utilisez la commande suivante :

git checkout -b nom_de_la_nouvelle_branche
Remplacez nom_de_la_nouvelle_branche par le nom que vous souhaitez donner à votre branche.

Effectuer des modifications : Apportez les modifications nécessaires à votre code.

Ajouter et valider les modifications : Ajoutez vos modifications et validez-les :

git add .
git commit -m "Message de commit"
Pousser la nouvelle branche vers le dépôt distant : Utilisez la commande suivante pour pousser votre nouvelle branche :

git push -u origin nom_de_la_nouvelle_branche
L'option -u permet de lier la branche locale à la branche distante, ce qui facilitera les futurs git push et git pull.

Exemple
Voici un exemple complet :

# Créer une nouvelle branche nommée "feature-xyz"
git checkout -b feature-xyz

# Apporter des modifications dans votre éditeur de code

# Ajouter les modifications
git add .

# Valider les modifications
git commit -m "Ajout de nouvelles fonctionnalités"

# Pousser la nouvelle branche vers GitHub
git push -u origin feature-xyz
Résumé
Utilisez git checkout -b nom_de_la_nouvelle_branche pour créer une nouvelle branche.
Utilisez git push -u origin nom_de_la_nouvelle_branche pour pousser la nouvelle branche.
