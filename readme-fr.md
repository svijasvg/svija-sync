[English version](https://github.com/svijasvg/svija-sync)

Svija Sync est un **script** : une petite appli qui ne fait qu'une tâche.

Tant qu'elle tourne, **elle synchronise votre site web avec votre ordinateur**.

Vous pouvez aussi vous en servir pour télécharger l'ensemble des fichiers nécessaires pour travailler sur votre site web.

# Téléchargement de l'app

1. Ouvrir le lien **svija-sync** ci-dessus dans une nouvelle fenêtre.

2. Cliquer le bouton vert en haut à droite **Clone or download** puis **Download ZIP**, puis fermer la page.

3. **Ouvrir le fichier .zip** sur votre ordinateur, si cela ne s'est pas fait automatiquement.

4. **Glisser le fichier TXT** choisi (anglais ou français) dans un dossier de travail où le site sera téléchargé.

*Mettez les autres fichiers dans la corbeille.*

# Codes d'authentification

1. **Cliquer deux fois sur le fichier TXT pour l'ouvrir** dans TextEdit.

2. Remplacer le « x » à la quatrième ligne par **les trois lignes en rouge** dans le mail que vous avez reçu de Svija :

```
site='example.com'  
user='example'  
pass='#r4nd0m#'  
```
*Sauvegerder la modification et quitter TextEdit.*

# Démarrer l'app

Renommer le script à **Svija Sync.commmand**. C'est une façon de dire à votre Mac que le document n'est plus un document mais une app.

**Cliquer deux fois sur l'app** pour la démarrer. Vous verrez peut-être un avertissement :

>Impossible d'ouvrir « Svija Sync.command » car cette app provient d'un développeur non identifié.

Pour l'autoriser, allez dans les **Préférences Sytème** › **Sécurité et confidentialité** › **Général**.

Vous verrez en bas un message similaire :
>L'utilisation de « Svija Sync.command » est bloquée car l'application provient d'un développeur non identifié.Cliquez le bouton **[Ouvrir quand même]**

# Une fois l'app démarréeSélectionnez **Downloader** pour créer le **dossier sync** contenant les fichiers de travail.

La première fois que vous vous connectez, **votre ordinateur vous demandera de valider l'identité du site web**.

Vous verrez un message en anglais :
>The authenticitiy of host _____ can't be established.  
>ECDSA key fingerprint is SHA256:lkjdqmlfkjqsdf098sdflkj.  
>Are you sure you want to continue connecting (yes/no)?
**Il faut taper « yes » puis retour** (et non pas y).Le script téléchargera alors les fichiers dans un nouveau dossier « sync », à côté de l'app Svija Sync.

# Qu'est-ce qu'il y a dedans ?

Tout ce dont vous avez besoin pour travailler sur votre site web :

* fichiers source d'Adobe Illustrator
* fichiers SVG exportés d'Illustrator, que vous ne manipulerez pas
* images importées, dans un sous-dossier « links »
* polices web et un sous-dosser « source » de polices Mac
* images diverses : le favicon, l'icône pour un raccourci iPhone, et une capture de la page d'accueil qui sera affichée lorsqu'un lien est posté sur les réseaux sociaux

# Usage de l'app

Quand vous voulez travailler sur votre site web, **cliquez deux fois sur « Svija Sync.command »** pour démarrer la synchronisation en continue.

Tant que l'app tourne, vous fichiers seront synchronisés tous les cinq secondes (apparition d'une nouvelle barre rouge).

# En suite…

Si vous comptez utiliser Svija régulièrement, les [scripts Svjia pour Illustrator](https://github.com/svijasvg/illustrator-scripts) vous faciliteront grandement la vie.

Vous pouvez les télécharger [ici](https://github.com/svijasvg/illustrator-scripts).