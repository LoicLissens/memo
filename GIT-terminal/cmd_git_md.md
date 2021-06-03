# **Commandes pour le terminal, git (et github) ainsi que markdown**

## **Terminal**

- cd 'nom du dossier': change de dossier (répertoire) vers le dossier ciblé
- cd .. : revien dans le répertoire précédent si on veut allé au chemin absolu pour allé dans appli cd /applications
- ls : affiche tous les fichiers présent dans le dossier on l'on se trouve
- ls -l : la même chose mais avec les permission.
- pwd : affiche le nom du dossier ou l'on se trouve
- touch 'nomdufichier.extension' : crée un fichier dans l'extension choisie (exemple .md ou .txt,...)
- mkdir 'nom du dossier': crée un dossier
- open 'nom du fichier' : ouvre un fichier avec la programme par défaut
- -a "nom de l'appli" 'nom du fichier': ouvre un fichier en précisant l'application qui va l'ouvrire.
- clear : Efface lesécritures dans le terminal
- GetFileInfo 'nom du fichier': affiche les infos d'un fichier
- mv : déplace un fichier entre répertoires (mv "le fichier à déplacer" "le fichier de destination" ) on peut aussi renomer avec mv (mv "fichier" "new_name")
- cp :copie un fichier ("fichier à copier" "l'endroit ou le copier")/ cp -r copie un répertoire
- rm : suprime un fichier (rm "nom du fichier") ou (rm -R "nom du dossier") pour un dossier
- rmdir: suprime un dossier
- man : man "nom d'une commande" ouvre le manuel de la commande (appuyer sur "q" pour quitter le manuel)
- cat : cat "nom d'un fichier" affiche le contenu du fichier
- less et more : less ou more "nom d'un fichier" affiche le contenu du fichier (on navigue avec les fleches) et q pour quitter
- grep : cherche des éléments dans un fichier ( grep "ce qu'on veut chercher" "la ou on veut le prendre")
- > : redirection: la redirection “>” pour envoyer le résultat d’une commande à l’intérieur d’un fichier.

---

- defaults write com.apple.finder AppleShowAllFiles TRUE : Afficher les dossier caché dans le finder comme les fichiers git (sur mac en tout cas) _retourner la même cmd avec false pour inverser_
- say 'mot ou phrase': fait parler le mac

# La syntaxe en Markdown

## Table des matières:

- [Modification du texte](#Modif)
- [Insérer des liens et des images](#liens)
- [Navigation dans des fichiers.md](#Nav)

## Modification du texte <a name="Modif"></a>:

- _Italique_ : `*italique*`
- **Gras** : `**gras**`
- **_Italique gras_** : `***italique gras***`
- ba̶r̶r̶é̶ : `~~barré~~`
- Titre :`# Titre`. A noter que comme en HTMl, il existe plusieurs taille de tire, au plus on rajoute de "#" au plus le titre sera petit.
- Insertion d'emoji :+1: : `:nom de l'emoji:` dans ce cas-ci `:+1:`. Voici une [liste](https://gist.github.com/rxaviers/7360908) des emojis présents en markdown sur github et il y en a un paquet :exclamation:
- Le barres de séparation : `-----------------` Il faut mettre minimum 3 tirets, astérisques, ou barre en bas :

---

## Insérer des liens et des images <a name="liens"></a>:

![Logo Beode](https://www.becode.org/register/assets/images/logo_Becode.png)

- Insertion d'images: `![Logo Beode](https://www.becode.org/register/assets/images/logo_Becode.png`
- [lien source openclasseroom](https://openclassrooms.com/fr/courses/1304236-redigez-en-markdown) : `[lien source openclasseroom](https://openclassrooms.com/fr/courses/1304236-redigez-en-markdown)`. C'est comme pour les images mais sans le "!".

---

## Navigation dans des fichiers.md <a name="Nav"></a> :</h2>

Markdown donne la possibilitée de navigué à l'intérieur d'un fichier .md ainsi qu'entre plusieurs fichier .md

- Navigation dans un même fichier:
  Pour naviguer au seins d'un même fichier, ce qui est pratique lorsque l'on veut faire une table des matières pas exemple.
  Si je veux faire pointer un lien en haut de mon texte vers une partie en aval il me sufit d'indentifier cette partie comme ceci:
  `## Mon premier paragraphe <a name="premierpara"></a>`. Ensuite de pointer cette identifiant de la même manière que si l'on pointait un lien : `1. [Lien vers mon premier paragraphe](#premierpara)`.

- Navigation entre plusieurs fichiers:
  Pour faire un lien pointant vers un autre fichier .md, rien de plus simple, c'est un peu comme en HTML. Si il provient d'un autre utilisateur github, ou d'un fichier dans un autre dépot, il sufit simplement de pointer vers son URL.
  Si c'est un fichier ou un sous dossier qui est dans le même dépot, c'est toujours similaire au HTML: `[texte du lien](Nom du dossier/fichier.md)` ou `[texte du lien](fichier.md)`.

---

## Index:

1. [Présentation du projet](README.md)
2. [Plus d'infos sur Markdown](whatismd.md)

## **Git**

- git init: crée un nouveau dépot dans un dossier vierge
- git add 'nom du fichier': ajoute le fichier après un changement pour le préparer à un commit
- git add \* : ajoute tous les fichiers
- git commit -m "Message de validation" : crée un snapshot des dernière modifications avec ce qui a été modifié
- git checkout 'nom de la branche': se positionne sur une branche (la branche de bae étant master et head le dernier sur le quele on a travaillé)
- git branch : affiche toutes les branches existante (celle précédé d'une astérixe est celle sur la quelle on se trouve)
- git branch 'nom d'une branche': crée une nouvelle branche
- git log : affiche les commits qui les à fait la date et la description des changements
- git pull : met à jour le dépot local avec les dernières modifs
- git remote add origin 'lien du serveur': clone et connect le dépot local avec le dépot distant
- git push origin 'nom de la branche à envoyer': envoie le dernier commit de la branche en qustion
- git clone 'lien github' : DL le répertoire
- !(Bon lien en français) [https://rogerdudler.github.io/git-guide/index.fr.html]
- Pour tracker une branche distante: git checkout --track nom_de_remote/nom_de_branch EX: git checkout --track origin/dev

https://github.github.com/training-kit/downloads/fr/github-git-cheat-sheet/ a completer avec ce lien

## **touche clavier mac**

- ~: alt + n
- \ : alt + MAJ + /
- {: alt + (
- [: alt+MAJ+(
- shit + cmd + r : refresh completement le programe
- | : alt + MAJ + L

* ctrl + cmd + space : **EMOJIIII**
