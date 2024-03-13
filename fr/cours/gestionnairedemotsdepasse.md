# Gestionnaire de mots de passe
Quel gestionnaire de mots de passe recommandons-nous ? Et pourquoi vous devez avoir un gestionnaire de mots de passe.
> [KeePassXC](https://keepassxc.org/) est de loin le meilleur, nous allons vous expliquer pourquoi.
## Sécurité
- Gratuit pour toujours.
- KeePass est recommandé par des organisations sérieuses : [https://keepass.info/ratings.html](https://keepass.info/ratings.html).
- Avec KeePass, vous pouvez obtenir une meilleure entropie que ProtonPass, par exemple.
- Vous pouvez verrouiller votre gestionnaire avec des clés de sécurité telles que Yubikey et autres. Il s'agit d'une fonction de sécurité supplémentaire importante.
- Les mots de passe sont également accessibles hors ligne.
- La possibilité d'ajouter des caractères inhabituels aux mots de passe.
> Conseils : Sauvegardez votre gestionnaire sur au moins deux supports. Un support physique et un autre dans le cloud, par exemple, est une bonne pratique.
## Licence
- KeePass est sous licence GPL-2 et GPL-3 entre autres, qui sont les meilleures licences pour les logiciels libres.
## L'équipe
- KeePass est toujours activement maintenu par l'équipe.
## Application mobile
- [KeePassDX](https://www.keepassdx.com/) sur Android est le gestionnaire parfait pour les smartphones.
  - Elle est toujours activement maintenue.
  - Facile à utiliser.
  - Aucune perte de fonctionnalité par rapport à KeePass.
  - Gratuit pour toujours.
  - Nombreuses options de personnalisation.
  - Licence GPL-3.
- Il existe également des applications KeePass pour iOS.
## Plus
- Large éventail d'options de personnalisation.
- Différences entre KeePass et KeePassXC
  - KeePassXC a une interface moderne, ce qui n'est pas le cas de Keepass. Entre les deux, prenez ce qui vous plaît. Ce sont les deux faces d'une même pièce.
# Mot de passe
Vous avez décidé de prendre KeePass, c'est bien. De bons mots de passe, c'est encore mieux.
## Laissez KeePass créer vos mots de passe
Vous avez le meilleur gestionnaire qui soit, et si vous l'utilisez correctement, vous en exploiterez toute la puissance.
> Nous pourrions vous apprendre ce qu'est un bon mot de passe, mais si nous vous apprenons à utiliser KeePass de manière optimale, nous gagnerons tous du temps et vous comprendrez en même temps.
## Configurez votre KeePass
### Installez KeePass
Sur le site officiel de KeePassXC, [https://keepassxc.org](https://keepassxc.org) si vous l'installez sur Windows, MacOS, Linux.
Ou [KeePass](https://keepass.info).
### Créez votre base de données
- Plus le temps de décryptage est long, plus votre protection est grande.
- Format de la base de données : KDBX 4 (recommandé).
- Paramètres avancés
  - Algorithme de cryptage : AES 256 bits (recommandé).
  - Fonction de dérivation de clé (KDF) : Argon2d [KDBX 4 - recommandé].
#### Confirmez et passez à l'étape suivante
- Entrez un mot de passe (recommandé).
- Ajoutez une autre protection (fortement recommandée) telle qu'une YubiKey ou une OnlyKey.
> L'importance de l'[authentification forte](https://github.com/kyvernfoundation/kyvern/blob/main/fr/cours/authentificationforte.md).
#### Confirmez et passez à l'étape suivante
- Enregistrez votre fichier de base de données.
> Félicitations, vous venez de créer votre gestionnaire de mots de passe.
### Laissez KeePass créer vos mots de passe
Si vous avez des questions, n'hésitez pas à nous contacter.
## Meilleures pratiques
- Sauvegardez votre base de données sur au moins deux supports différents. Sur le cloud et sur une clé USB, par exemple.
  - Effectuez votre sauvegarde après chaque modification de votre base de données.
- Si vous souhaitez aider une personne de votre entourage à renforcer sa sécurité, partagez ce tutoriel avec elle, afin qu'elle soit au courant des dernières mises à jour et que vous ne risquiez pas de vous compromettre.
