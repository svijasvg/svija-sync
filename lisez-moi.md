[English Version](https://github.com/svijasvg/svija-sync) · [Document source](https://docs.svija.com/fr/quick-start/1-1-svija-sync)

Svija Sync 1.1.1
-------------------------------------

**Svija Sync** est un **script** : une petite appli qui ne fait qu'une tâche.

Tant qu'elle tourne, **elle synchronise votre site web avec votre ordinateur**.

Vous pouvez aussi vous en servir pour télécharger l'ensemble des fichiers nécessaires pour travailler sur votre site web.

Version abrégée
---------------

*Pour utilisateurs avisés ; voir plus bas pour la description exhaustive.*  
*Un astérisque indique qu'il peut y avoir une alerte sécuritaire au moment de la manipulation.

**Télécharger Svija Sync** sur [github.com/svijasvg/svija-sync](https://github.com/svijasvg/svija-sync).

Créer un dossier de travail et mettre **Svija Sync.command 0.0.0-fr.txt** dedans.

Ouvrir le fichier et **remplacer le « x » seul** par les quatre lignes rouges dans le mail que vous avez reçu de Svija :

    name='Prenom'  
    site='example.com'  
    user='example'  
    pass='eY-v354strs'  

**Remplacer « Prenom » avec votre prenom**, puis renommer le script* :

    sync.command 0.0.0-fr.txt devient  
    sync.command

**Cliquer deux fois** sur Svija-Sync.command pour le démarrer.*

Au premier démarrage, choisir **Downloader**.*

Le script téléchargera tous les fichiers de votre site dans **un nouveau dossier « sync »**, à côté de Svija Tools.

Version exhaustive
------------------

#### Télécharger Svija Sync

1.  Aller sur [github.com/svijasvg/svija-sync](https://github.com/svijasvg/svija-sync)
2.  Cliquer sur **Clone or download** (bouton vert)
3.  Sélectionner **Download ZIP**

**Ouvrir le fichier ZIP téléchargé** (s'il ne s'est pas ouvert automatiquement).

* * * * *

#### Déplacer Svija Sync

1.  Créer un **dossier de travail** pour votre site web
2.  **Glisser Svija Sync.command 0.0.0-fr.txt** dans le dossier
3.  Mettre les autres fichiers **dans la corbeille**

* * * * *

#### Configurer Svija Sync

Sur votre ordinateur :

1.  **Cliquer deux fois sur Svija Sync.command 0.0.0-fr.txt** pour l'ouvrir dans TextEdit
2.  **Remplacer le « x » seul** par les trois lignes rouges dans le mail que vous avez reçu de Svija :  
    site='example.com'  
    user='example'  
    pass='eY-v354strs'  
3.  **Fermer le document**
4.  **Renommer le document**

Enlever la partie **après .command** :


    Svija Sync.command 0.0.0-fr.txt   devient  
    Svija Sync.command

Vous êtes susceptible de voir l'avertissement suivant :

![avertissement changement d'extension](https://docs.svija.com/wp-content/uploads/elementor/thumbs/avertissement-changement-dextension-omnbsrj1hhojppnd206fdsw7n5c7a9vqcl0vvr8efw.jpg "avertissement changement d'extension")

**Cliquer « Utiliser .command ».**

Le fait de changer l'extension du fichier veut dire que la prochaine fois qu'il est ouvert, il se lancera en tant qu'application et pas en fichier texte.

* * * * *

#### Démarrer Svija Sync

**Cliquer deux fois** sur Svija Sync.command pour le démarrer.

Si vous ne voyez pas cet avertissement vous pouvez continuer plus bas :

![avertissement impossible d'ouvrir](https://docs.svija.com/wp-content/uploads/elementor/thumbs/avertissement-impossible-douvrir-omnbtjq76irt4gmkpl8hk1qupkhadmhg9pdc8afyjo.jpg "avertissement impossible d'ouvrir")

Pour continuer, aller dans les **Préférences Système › Sécurité et confidentialité › Général** :

![avertissement bloqué](https://docs.svija.com/wp-content/uploads/elementor/thumbs/avertissement-bloqué-omnbujg2e88sp41k4r60lyqg1wfhoinrrpq723yt38.jpg "avertissement bloqué")

**Cliquez sur « Ouvrir quand même ».**

Le script devrait alors démarrer normalement, et vous verrez :

![svija sync - démarrage](https://docs.svija.com/wp-content/uploads/elementor/thumbs/svija-sync-démarrage-omnbv7vvbx1wco80rbg2v5ojr25n9y0bu670eu5viw.jpg "svija sync -- démarrage")

**Appuyer sur la touche D puis retour**

La première fois que vous vous connectez à votre site, votre ordinateur vous demandera d'accepter l'authenticité du site.

Vous verrez un message en anglais :

    The authenticitiy of host nom & IP de votre site can't be established...  
    ECDSA key fingerprint is SHA256:lkjdqmlfkjqsdf098sdflkj...  
    Are you sure you want to continue connecting (yes/no)?

**Il faut taper « yes »** puis retour (et non pas y).

L'application téléchargera alors les fichiers dans un nouveau dossier « sync », à côté de Svija Tools :

-   **admin** : logo et couleurs pour Svija Admin
-   **desktop** : contenus du site, version ordinateur
-   **fonts** : polices nécessaires
-   **images** : favicon, Apple touch icon, capture de la page d'accueil
-   **mobile** : contenus du site, version mobile
-   **scripts** : scripts utilisés pour animations, effets spéciaux etc.