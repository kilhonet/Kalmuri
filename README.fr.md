# Kalmuri

**Un outil de capture gratuit pour Windows : plein écran, région, fenêtre ou page web entière d'une seule touche de raccourci, et enregistrement de l'écran en MP4.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · Français

> Ce document est une traduction. En cas de différence, la [version coréenne](README.ko.md) fait foi.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-4.3.1-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/kalmuri?lang=fr)

![Écran de Kalmuri](images/kalmuri-en.webp)

## Présentation

Avec Kalmuri, vous ne choisissez que deux choses — quoi capturer (**Capture**) et comment le conserver (**Enregistrer dans**) — et ensuite une simple pression sur `PrintScreen` fait tout le reste. Pas de fenêtre à ouvrir ni de nom de fichier à taper à chaque fois : les résultats s'accumulent dans le dossier d'enregistrement sous `K-001.png`, `K-002.png`, etc.

Vous pouvez capturer tout l'écran, une région fixe, une zone tracée à la souris, la fenêtre que vous utilisez, un seul bouton dans une fenêtre, ou toute une page web qui défile. Le même raccourci permet aussi d'enregistrer l'écran en MP4, de relever les codes couleur de l'écran et de transformer le texte d'une image en fichier texte.

Fermer la fenêtre laisse Kalmuri fonctionner dans la zone de notification (barre d'état système) : une fois lancé, vous pouvez capturer à tout moment avec le raccourci.

## Fonctionnalités

- **7 modes de capture** — Plein écran, région fixe, zone glissée, fenêtre active, contrôle de fenêtre, page web entière et pipette.
- **Nombreux types de sortie** — Fichiers PNG · JPG · GIF · BMP · WebP, vidéo MP4, reconnaissance de texte (TXT), presse-papiers, partage d'image, imprimante et image flottante à l'écran.
- **Enregistrement de l'écran** — Enregistrez le plein écran ou une région en MP4, avec le son joué sur votre PC si vous le souhaitez.
- **Capture de page web entière** — Enregistrez une page ouverte dans Edge · Chrome en une seule image, jusqu'en bas du défilement.
- **Reconnaissance de texte (OCR)** — Enregistrez le texte de l'écran capturé dans un fichier texte.
- **Pipette** — Copiez la couleur sous le curseur au format HEX · RGB · Web · TColor.
- **Partage des captures** — Envoyez une capture sur le web et ouvrez-la aussitôt pour partager le lien.
- **Flottant** — Gardez une image capturée au premier plan, à l'endroit même de la capture, comme référence.
- **Réglage de la région au clavier** — Ajustez la région au pixel près avec les flèches · `Ctrl`+flèche · `Shift`+flèche.
- **Réglages pratiques** — Raccourci personnalisable, format du nom de fichier (numérotation · date et heure), son de capture, inclusion du curseur, lancement au démarrage.
- **8 langues** — Coréen · anglais · japonais · chinois · russe · italien · français · espagnol.

## Téléchargement / Installation

| Type | Lien |
|---|---|
| Version à installer | [Télécharger](https://down.kilho.net/kalmuri?lang=fr) |
| Version portable (ZIP) | [Télécharger](https://down.kilho.net/kalmuri?lang=fr&nosetup) |

La version à installer lance Kalmuri dès la fin de l'installation et active **Lancer au démarrage du système** : Kalmuri démarre dans la barre d'état à chaque démarrage de Windows. Pour la version portable, décompressez le ZIP et lancez `Kalmuri.exe`.

La version portable ne contient que l'exécutable : **l'enregistrement MP4 et l'enregistrement WebP ne sont disponibles que dans la version installée**. Tout le reste est identique dans les deux versions.

## Utilisation

### Premiers pas

1. Lancez Kalmuri. Une petite fenêtre s'ouvre et l'icône de Kalmuri apparaît dans la zone de notification.
2. Sous **Capture**, choisissez quoi capturer. Par défaut : **Plein écran**.
3. Sous **Enregistrer dans**, choisissez comment le conserver. Par défaut : **PNG**. Choisir JPG · WebP affiche une case de qualité à côté ; choisir TXT affiche une case de langue de reconnaissance.
4. Appuyez sur `PrintScreen`. Avec un bruit d'obturateur, la capture est enregistrée dans le dossier d'enregistrement (le bureau au départ) sous `K-001.png`.
5. Cliquez sur **Ouvrir le dossier** pour ouvrir le dossier d'enregistrement et voir le résultat.
6. Fermer la fenêtre laisse Kalmuri actif dans la barre d'état. Cliquez sur l'icône pour rouvrir la fenêtre, et faites un **clic droit** sur la fenêtre ou l'icône pour le menu des réglages.

### Organisation de l'écran

**Fenêtre principale**

| Élément | Rôle |
|---|---|
| **Capture** | Choisir quoi capturer (tableau ci-dessous) |
| **Enregistrer dans** | Choisir comment conserver la capture (tableau ci-dessous). JPG · WebP affichent une case de qualité (100 – 60), TXT une case de langue de reconnaissance |
| **Ouvrir le dossier** | Ouvre le dossier d'enregistrement dans l'Explorateur |
| **Créé par Kilho** | Ouvre la page de présentation de Kalmuri |

**Capture**

| Élément | Ce qui est capturé |
|---|---|
| **Plein écran** | Tout l'écran |
| **Région** | L'intérieur d'une fenêtre à cadre rouge — pour capturer le même endroit et la même taille à chaque fois |
| **Glisser** | La zone tracée à la souris après avoir appuyé sur le raccourci |
| **Fenêtre active** | La fenêtre que vous utilisez |
| **Contrôle de la fenêtre** | La fenêtre ou l'élément (bouton, panneau…) sous le curseur |
| **Navigateur Web** | Toute la page web affichée dans Edge · Chrome, jusqu'en bas du défilement |
| **Pipette** | Le code couleur sous le curseur |

**Enregistrer dans**

| Élément | Résultat |
|---|---|
| **PNG** · **JPG** · **GIF** · **BMP** · **WebP** | Un fichier image dans ce format |
| **Vidéo(MP4)** | Enregistrement de l'écran (Plein écran · Région uniquement) |
| **TXT** | Reconnaît le texte de l'écran capturé et l'enregistre dans un fichier texte |
| **Presse-papiers** | Copie dans le presse-papiers uniquement, sans fichier |
| **Télécharger Imgbox** | Envoie l'image sur le web et ouvre sa page dans le navigateur |
| **Imprimante** | Imprime aussitôt |
| **Flottant** | Garde l'image au premier plan, à l'endroit de la capture |

**Menu du clic droit** (fenêtre principale ou icône de la barre d'état)

| Élément | Rôle |
|---|---|
| **Ouvrir le dossier de sauvegarde** · **Paramètres du dossier** | Ouvrir ou changer le dossier d'enregistrement |
| **Paramètres de capture** | **Son de capture** (Aucun · Avant la capture · Après la capture) · **Curseur de la souris** · **Avec presse-papiers** |
| **Paramètres d'enregistrement** | **Limiter le temps d'enregistrement** (Illimité · 30 minutes · 1 heure · 2 heures · 4 heures) · **Curseur de la souris** · **Inclure le son** |
| **Paramètres de langue** | Langue de l'interface |
| **Paramètres du nom de fichier** | **Numéro incrémental automatique #1** · **Numéro incrémental automatique #2** · **Date et heure** |
| **Paramètres des raccourcis** | Changer le raccourci de capture |
| **Lancer au démarrage du système** | Démarrer automatiquement dans la barre d'état au démarrage de Windows |
| **Créé par Kilho** · **Quitter** | Page de présentation · quitter le programme |

### Que faire quand…

**Capturer tout l'écran d'un coup**
Laissez **Capture** sur **Plein écran** et appuyez sur `PrintScreen`. Inutile d'ouvrir la fenêtre : tant que Kalmuri est dans la barre d'état, la capture fonctionne partout.

**Capturer le même endroit et la même taille à chaque fois**
Choisissez **Région** : une fenêtre à cadre rouge clignotant apparaît. Faites glisser le cadre pour le déplacer, faites glisser ses bords pour le redimensionner, puis appuyez sur `PrintScreen` pour ne capturer que l'**intérieur** du cadre. La taille actuelle (par ex. `480x360`) s'affiche en haut du cadre, et sa position et sa taille sont mémorisées pour la fois suivante. Le X en haut à droite ferme le cadre et revient à **Plein écran**.

**Ajuster la région au pixel près**
Cliquez sur le cadre de la région et utilisez le clavier. Les flèches le **déplacent** de 1 pixel ; `Ctrl`+flèche le **redimensionne** de 10 pixels et `Shift`+flèche de 1 pixel. Dégrossissez à la souris, puis finissez au clavier.

**Mémoriser les tailles que vous utilisez souvent**
Un clic droit sur le cadre affiche une liste de tailles comme `320x240` · `640x480` · `720x480` pour changer en un clic. Modifiez ces tailles dans **Paramètre** en saisissant la largeur et la hauteur de **Perso #1 – #3**. Saisissez des valeurs sous **Actuel** et cliquez sur **Appliquer** pour donner cette taille à la région actuelle. **Cacher**, dans le même menu, masque simplement le cadre pour l'instant.

**Choisir à la souris juste la partie voulue**
Choisissez **Glisser** et appuyez sur `PrintScreen` : l'écran se fige et s'assombrit. Tracez la partie à capturer et relâchez pour n'enregistrer qu'elle. `Esc` annule. Comme c'est l'instant figé qui est capturé, vous pouvez même saisir un menu ouvert ou une notification qui ne s'affiche qu'un instant.

**Capturer uniquement la fenêtre que vous utilisez**
Choisissez **Fenêtre active**, cliquez sur la fenêtre pour la mettre au premier plan, puis appuyez sur `PrintScreen`. Le bureau et les autres fenêtres sont exclus ; seule cette fenêtre est enregistrée.

**Capturer un seul bouton ou panneau d'une fenêtre**
Choisissez **Contrôle de la fenêtre** : un cadre en pointillés suit l'élément sous le curseur. Survolez le bouton, le champ ou le panneau voulu et appuyez sur `PrintScreen` pour n'enregistrer que l'élément encadré — pratique pour découper une seule partie pour un manuel ou une demande d'assistance.

**Enregistrer une longue page web en une seule image**
Choisissez **Navigateur Web** : Kalmuri ouvre une fenêtre Edge séparée (Chrome si Edge est absent). Ouvrez-y la page voulue et appuyez sur `PrintScreen` : toute la page, y compris la partie qu'il faudrait faire défiler, est enregistrée en une image. Avec plusieurs onglets ouverts, c'est l'onglet affiché qui est capturé. Fermer cette fenêtre de navigateur revient à **Plein écran**. Nécessite Windows 8 ou ultérieur, avec Edge ou Chrome installé.

**Trouver le code couleur d'un élément à l'écran**
Choisissez **Pipette** : la fenêtre affiche en temps réel la couleur et le code sous le curseur. Placez le curseur où vous voulez et appuyez sur `PrintScreen` : la couleur est ajoutée en haut de la liste et copiée dans le presse-papiers. Un clic droit sur la liste → **Format** permet de choisir le format de copie — **HEX** (`FF9933`) · **RGB** (`255, 153, 51`) · **Web** (`#FF9933`) · **TColor** (`$003399FF`) — et les commandes **Copier** · **Supprimer** du même menu permettent de gérer la liste.

**Enregistrer l'écran en vidéo**
Réglez **Enregistrer dans** sur **Vidéo(MP4)** et appuyez sur `PrintScreen` pour lancer l'enregistrement ; la fenêtre affiche **En cours** et le temps écoulé. Appuyez de nouveau sur `PrintScreen` pour arrêter et enregistrer le fichier MP4. L'enregistrement fonctionne avec **Plein écran** et **Région** ; pendant l'enregistrement d'une région, `[REC]` et le temps s'affichent sur le cadre et la région est verrouillée.

**Enregistrer aussi le son de votre PC**
Activez **Paramètres d'enregistrement → Inclure le son** pour enregistrer, avec l'image, le son joué sur votre PC (vidéos, jeux, notifications). Activez-le pour enregistrer un cours ou la lecture d'une vidéo.

**Laisser un enregistrement tourner en votre absence**
Réglez **Paramètres d'enregistrement → Limiter le temps d'enregistrement** sur **30 minutes** · **1 heure** · **2 heures** · **4 heures** : l'enregistrement s'arrête tout seul une fois ce temps écoulé — fini le disque plein parce que vous avez oublié de l'arrêter.

**Retirer le curseur des enregistrements**
Désactivez **Paramètres d'enregistrement → Curseur de la souris** pour masquer le curseur dans les vidéos. Ce réglage est distinct de **Paramètres de capture → Curseur de la souris** pour les captures : vous pouvez exclure le curseur des captures d'écran mais le garder dans les vidéos, ou l'inverse.

**Transformer le texte d'une image en texte**
Réglez **Enregistrer dans** sur **TXT** : une case de langue de reconnaissance apparaît à côté. Choisissez la langue du texte et capturez : le texte à l'écran est lu et enregistré dans un fichier texte (`K-001.txt`). Idéal pour le texte d'images ou de documents impossibles à copier. Combinez-le avec **Glisser** pour ne reconnaître que le paragraphe voulu. La liste des langues correspond aux langues de reconnaissance de texte installées dans Windows.

**Coller aussitôt une capture ailleurs**
Réglez **Enregistrer dans** sur **Presse-papiers** pour copier la capture dans le presse-papiers seulement, sans créer de fichier, et la coller dans une messagerie ou un document avec `Ctrl`+`V`. Pour garder un fichier et coller en plus, activez **Paramètres de capture → Avec presse-papiers** : quel que soit le format d'enregistrement, la capture est aussi copiée dans le presse-papiers.

**Partager une capture par un lien**
Réglez **Enregistrer dans** sur **Télécharger Imgbox** et capturez : l'image est envoyée sur le web et sa page s'ouvre dans votre navigateur. Copiez l'adresse et envoyez-la pour partager la capture sans pièce jointe.

**Imprimer dès la capture**
Réglez **Enregistrer dans** sur **Imprimante** : la capture est imprimée aussitôt sur l'imprimante par défaut.

**Garder une capture à l'écran comme référence**
Réglez **Enregistrer dans** sur **Flottant** et capturez : une image de même taille reste au premier plan, à l'endroit même de la capture. Faites-la glisser pour la déplacer — pratique pour recopier des valeurs ou comparer deux écrans. Un clic droit sur l'image → **Enregistrer l'image** l'enregistre en PNG · JPG · GIF · BMP · WebP ; **Supprimer les éléments flottants** · **Supprimer tous les éléments flottants** la ferment.

**Réduire la taille des fichiers**
Réglez **Enregistrer dans** sur **JPG** ou **WebP** et choisissez 100 · 90 · 80 · 70 · 60 dans la case de qualité à côté (90 par défaut). Plus le nombre est petit, plus le fichier est léger. Le PNG convient aux écrans chargés de texte ; le JPG · WebP aux écrans riches en photos.

**Changer la règle de nommage des fichiers**
Choisissez dans **Paramètres du nom de fichier**.
- **Numéro incrémental automatique #1** (par défaut) — continue à partir du plus grand numéro du dossier (`K-001`, `K-002` …).
- **Numéro incrémental automatique #2** — remplit à partir du plus petit numéro libre. Si vous avez supprimé un fichier au milieu, son numéro est réutilisé.
- **Date et heure** — nomme les fichiers selon l'heure de capture (`K-20260928-153012345`). Pratique pour classer par ordre chronologique des captures faites sur plusieurs jours.

Quelle que soit la règle, un fichier du même nom n'est jamais écrasé : la capture est enregistrée sous un nouveau nom.

**Changer le dossier d'enregistrement**
Choisissez un dossier avec **Paramètres du dossier**. Par défaut, c'est le bureau. **Ouvrir le dossier de sauvegarde** (ou **Ouvrir le dossier** dans la fenêtre) ouvre ce dossier à tout moment.

**Changer le raccourci**
Dans **Paramètres des raccourcis**, cochez `Ctrl` · `Alt` · `Shift`, choisissez une touche et cliquez sur **OK**. Vous pouvez choisir `PrintScreen`, `A` – `Z`, `0` – `9`, `F1` – `F12` ou `DEL`. Si un autre programme utilise déjà cette combinaison, vous en êtes averti : choisissez-en une autre.

**Quand `PrintScreen` ouvre l'Outil Capture de Windows**
Windows 11 propose un réglage qui fait ouvrir l'Outil Capture à `PrintScreen`. Kalmuri désactive ce réglage à son lancement pour que `PrintScreen` fonctionne avec Kalmuri.

**Changer le son de capture**
Sous **Paramètres de capture → Son de capture**, choisissez **Aucun** · **Avant la capture** (par défaut) · **Après la capture**. **Aucun** convient aux endroits calmes ; **Après la capture** vous indique par un son que l'enregistrement est terminé.

**Inclure ou exclure le curseur**
Avec **Paramètres de capture → Curseur de la souris** activé (par défaut), le curseur apparaît sur les captures. Gardez-le pour les captures qui désignent un bouton ; désactivez-le pour un écran net.

**L'avoir prêt à chaque démarrage de Windows**
Avec **Lancer au démarrage du système** activé, Kalmuri démarre dans la barre d'état sans fenêtre au démarrage de Windows, prêt pour le raccourci. C'est activé d'emblée dans la version installée.

**Continuer après avoir fermé la fenêtre, ou quitter vraiment**
Le X de la fenêtre ne quitte pas Kalmuri : il le cache dans la barre d'état. Pour quitter complètement, cliquez sur **Quitter** dans le menu du clic droit et confirmez. Si un enregistrement est en cours, arrêtez-le d'abord, puis quittez.

**Changer la langue de l'interface**
Choisissez 한국어 · English · 日本語 · 中文 · Русский · Italiano · Français · Español dans **Paramètres de langue** : le changement est immédiat.

### Droits d'auteur

Les écrans que vous capturez ou enregistrez avec Kalmuri peuvent contenir des textes, images, vidéos ou musiques appartenant à d'autres. Les partager ou les publier au-delà d'un usage personnel de conservation et de référence peut nécessiter l'autorisation du titulaire des droits : respectez les conditions d'utilisation de chaque service et le droit d'auteur.

## Configuration

Chaque réglage est enregistré dès que vous le modifiez et réutilisé au prochain lancement.

| Élément | Par défaut |
|---|---|
| Capture | Plein écran |
| Enregistrer dans | PNG |
| Qualité JPG · WebP | 90 |
| Dossier d'enregistrement | Bureau |
| Paramètres du nom de fichier | Numéro incrémental automatique #1 |
| Raccourci | `PrintScreen` |
| Son de capture | Avant la capture |
| Curseur de la souris (capture · enregistrement) | Activé |
| Avec presse-papiers | Désactivé |
| Limiter le temps d'enregistrement | Illimité |
| Inclure le son | Désactivé |
| Lancer au démarrage du système | Activé dans la version installée |
| Langue | Suit le paramètre de région de Windows (anglais si la langue n'est pas prise en charge) |

## Configuration requise

- Windows 10 · Windows 11
- La capture **Navigateur Web** nécessite Microsoft Edge ou Google Chrome.
- **TXT** (reconnaissance de texte) utilise les langues de reconnaissance de texte installées dans Windows.
- La connexion Internet ne sert qu'aux avis de nouvelle version, à **Télécharger Imgbox** et à la capture **Navigateur Web**.

## Mises à jour

Kalmuri ne se met **pas** à jour tout seul. Au démarrage, il vérifie s'il existe une nouvelle version et affiche un avis ; cliquer sur **[Oui]** ouvre la page de téléchargement et ferme le programme. Les nouvelles versions sont publiées manuellement après des tests internes et annoncées sur la [page de Kalmuri](https://kilho.net/kalmuri). Consultez l'[avis sur la politique de mise à jour](https://en.kilho.net/archives/notice/2940).

## Licence

Kalmuri est un **gratuiciel**. Vous pouvez l'utiliser gratuitement et sans restriction partout — au bureau, à la maison, dans les administrations ou à l'école — et le redistribuer librement.

## Liens

- Site web : <https://kilho.net/kalmuri>
- Forum : <https://kilho.top/forum/qna>
- X (Twitter) : <https://www.twitter.com/kilhonet>

© KILHO.NET
