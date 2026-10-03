# WorldView

**Une visionneuse d'images gratuite pour Windows, pour parcourir rapidement et confortablement images, archives et documents PDF.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · Français

> Ce document est une traduction. En cas de différence, la [version coréenne](README.ko.md) fait foi.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/worldview?lang=fr)

![Écran de WorldView](images/worldview-ko.webp)

## Présentation

WorldView permet de feuilleter des dossiers remplis de photos, de lire des archives de bandes dessinées deux pages à la fois sans les décompresser, et de faire défiler des webtoons comme une seule bande continue. Les documents PDF s'ouvrent de la même façon, page par page.

Déposez une image sur la fenêtre : elle s'ouvre aussitôt, et les autres images du même dossier suivent dans l'ordre. L'écran n'affiche que l'image ; les boutons n'apparaissent que lorsque vous approchez la souris du haut ou du bas de la fenêtre.

L'affichage est assuré par la carte graphique, si bien que même les grandes photos se zooment en douceur, et les pages précédente et suivante sont lues à l'avance pour que tourner une page ne fasse presque jamais attendre.

## Fonctionnalités

- **Nombreux formats d'image** — JPEG, PNG, GIF, WebP, TIFF, BMP, SVG, JPEG XL, HEIC, AVIF, PSD, RAW d'appareil photo, etc.
- **Archives sans décompression** — Feuilletez une à une les images contenues dans des archives ZIP, RAR, 7Z, CBZ, CBR, EGG, ALZ, etc.
- **Documents PDF** — Chaque page est une image ; en zoomant, la page est redessinée à cette taille pour garder un texte net.
- **Quatre modes d'affichage** — Une page, deux pages (gauche→droite / droite→gauche), première page en couverture, webtoon continu.
- **Images animées** — Lecture des GIF, APNG et WebP animés.
- **Rotation automatique et correction des couleurs** — Les photos prises à la verticale s'ouvrent dans le bon sens, et celles qui ont un profil de couleur s'affichent avec leurs vraies couleurs.
- **Zoom et navigateur** — Zoom centré sur le curseur ; quand l'image déborde, le navigateur en bas à droite vous emmène directement n'importe où.
- **Infos de l'image et EXIF** — Une pression sur `Tab` affiche les infos du fichier ainsi que la date de prise de vue, l'appareil, l'objectif et l'exposition.
- **Fonctions pratiques** — Associations de fichiers, plein écran, toujours au premier plan, fichiers récents, reprise là où vous vous étiez arrêté, suppression vers la Corbeille, raccourcis personnalisables.
- **8 langues** — Coréen · anglais · japonais · chinois · russe · italien · français · espagnol.

## Téléchargement / Installation

| Type | Lien |
|---|---|
| Version à installer | [Télécharger](https://down.kilho.net/worldview?lang=fr) |
| Version portable (ZIP) | [Télécharger](https://down.kilho.net/worldview?lang=fr&nosetup) |

La version à installer ouvre WorldView dès la fin de l'installation. Pour la version portable, décompressez le ZIP et lancez `WorldView.exe` — le dossier `vendor` doit rester à côté de l'exécutable. Les paramètres sont enregistrés dans le dossier du programme : si vous emportez la version portable sur une clé USB, vos paramètres vous suivent.

Aucune des deux versions ne crée d'associations de fichiers d'elle-même. Pour ouvrir vos images dans WorldView par double-clic, activez-les dans **Paramètres → Associations** (voir « Que faire quand… » plus bas).

## Utilisation

### Premiers pas

1. Lancez WorldView et déposez sur la fenêtre un fichier image, un dossier, une archive ou un PDF. Vous pouvez aussi choisir un fichier avec le bouton dossier de la barre inférieure ou la touche `O`.
2. L'image s'ouvre ajustée à la fenêtre, et les autres images du même dossier forment une liste par ordre de nom. Le titre en haut indique où vous en êtes, par exemple `Dossier > Nom du fichier [69/308]`.
3. Tournez la molette ou appuyez sur `←` `→` · `PageUp` `PageDown` pour passer à la page précédente ou suivante. Vous pouvez aussi cliquer sur les boutons fléchés qui apparaissent quand la souris s'approche des bords gauche et droit.
4. Approchez la souris du bas de la fenêtre pour afficher la barre inférieure. Elle contient les boutons de zoom, de rotation et de page ainsi qu'une barre de navigation : faites-la glisser pour aller directement à n'importe quelle page.
5. Le bouton **Affichage** à droite de la barre inférieure permet de choisir le zoom (ajuster à la fenêtre, taille réelle, largeur, hauteur) et le mode d'affichage (une page, deux pages, webtoon). Votre choix est mémorisé pour la page suivante et le prochain lancement.
6. Faites un **clic droit** n'importe où dans la fenêtre pour ouvrir le menu : Ouvrir un fichier, Fichiers récents, Afficher dans l'Explorateur, Supprimer le fichier, Paramètres.

### Organisation de l'écran

**Barre supérieure** (apparaît quand la souris s'approche du haut de la fenêtre)

| Élément | Rôle |
|---|---|
| Icône de l'application | Ouvre le même menu que le clic droit |
| Titre | Dossier > nom du fichier [page actuelle/total]. `Chargement` s'ajoute pour les pages longues à lire |
| Punaise | Active ou désactive **Toujours au premier plan** |
| Réduire · `[]` · Fermer | `[]` bascule en plein écran |

**Barre inférieure** (apparaît quand la souris s'approche du bas de la fenêtre)

| Bouton | Rôle |
|---|---|
| Dossier | Ouvrir un fichier |
| `+` · `−` | Agrandir · réduire |
| Rotation | Rotation de 90° dans le sens horaire |
| `‹` · `›` | Page précédente · page suivante |
| Barre de navigation | Glisser ou cliquer pour aller à n'importe quelle page |
| Affichage | Le menu Affichage — zoom, deux pages, couverture, webtoon |
| Engrenage | Paramètres |

**Menu du clic droit**

| Élément | Rôle |
|---|---|
| **Ouvrir un fichier** · **Ouvrir un dossier** | Choisir un fichier ou un dossier à ouvrir |
| **Fichiers récents** | Les 5 derniers éléments ouverts |
| **Afficher dans l'Explorateur** | Ouvre l'Explorateur avec le fichier actuel sélectionné |
| **Affichage** | Le même menu que le bouton Affichage de la barre inférieure |
| **Supprimer le fichier** | Envoie le fichier actuel vers la Corbeille |
| **À propos de WorldView** · **Paramètres** · **Quitter** | Page de présentation · fenêtre des paramètres · quitter |

**Paramètres** — Les changements s'appliquent immédiatement ; il n'y a pas de bouton `OK`. **Réinitialiser**, en bas à gauche, rétablit tous les paramètres par défaut et supprime aussi les associations de fichiers.

| Page | Éléments |
|---|---|
| **Général** | Quitter avec Échap · Confirmer la suppression · Rouvrir le dernier fichier au démarrage · Toujours au premier plan · Journal · Langue |
| **Affichage** | Zoom · Affichage · Première page en couverture · Pages larges seules · Barres de défilement · EXIF dans les infos · Afficher le navigateur · Boutons fléchés latéraux · Au premier/dernier fichier |
| **Associations** | Extensions à ouvrir dans WorldView par double-clic |
| **Raccourcis** | Changer la touche de chaque action |

### Que faire quand…

**Feuilleter les photos d'un dossier**
Déposez ou double-cliquez une photo : les images de ce dossier forment une liste par ordre de nom. Les nombres sont triés comme des nombres, donc `photo2.jpg` passe avant `photo10.jpg`. Tournez les pages avec la molette · `←` `→` · `PageUp` `PageDown` · `Space`, et allez à la première et à la dernière page avec `Home` `End`.

**Lire une archive de BD sans la décompresser**
Déposez telle quelle une archive ZIP · RAR · 7Z · CBZ · CBR : les images qu'elle contient se tournent une à une. Ni décompression ni dossier temporaire. Les dossiers internes de l'archive s'affichent à la suite, par ordre de nom.

**Lire tout un dossier bibliothèque**
Déposez un dossier : WorldView parcourt tous les sous-dossiers, déplie page par page les archives et PDF qu'ils contiennent et en fait une seule liste. Vous lisez du début à la fin sans ouvrir chaque tome séparément.

**Choisir plusieurs éléments et ne voir qu'eux**
Sélectionnez plusieurs fichiers, dossiers ou archives dans l'Explorateur et déposez-les ensemble : seule votre sélection forme la liste. Les fichiers voisins non choisis n'y entrent pas.

**Lire une BD deux pages à la fois**
Choisissez **Affichage** → **Deux pages (gauche→droite)** pour afficher deux pages côte à côte comme un livre. Pour les mangas, qui se lisent de droite à gauche, choisissez **Deux pages (droite→gauche)**. Même avec un nombre impair de pages, la dernière garde sa moitié d'écran au lieu de s'agrandir soudain.

**Quand la couverture décale les paires**
Si la page 1 est une couverture et que chaque double page semble décalée d'une page, activez **1re page en couverture**. La couverture est seule, puis les pages s'associent en 2-3, 4-5, etc.

**BD avec des illustrations en double page**
Activez **Pages larges seules** : une image large, numérisée sur deux pages, s'affiche seule et en grand, tandis que les autres continuent d'aller par deux.

**Lire un webtoon en une bande continue**
Activez **Affichage** → **Webtoon (continu)** : toutes les pages sont mises bout à bout verticalement à la largeur de la fenêtre, il suffit de faire défiler. Faites glisser la barre de défilement à droite pour aller n'importe où dans l'ensemble.

**Une seule image très haute**
Une image plus de trois fois plus haute que large s'ouvre ajustée à la largeur, **en partant du haut**. Descendez avec la molette · `↑` `↓` · `Space` ; arriver en bas ne fait pas sauter à la page suivante, vous ne perdez donc jamais votre place. Passez à la page suivante avec `PageDown` ou le bouton fléché. `Ctrl`+`Home` / `Ctrl`+`End` vont directement tout en haut ou tout en bas de l'image.

**Lire un PDF page par page**
Déposez un PDF : chaque page se tourne comme une image. Vous pouvez aussi l'ouvrir comme un livre en mode deux pages, ou le faire défiler en mode webtoon. En zoomant ou en agrandissant la fenêtre, la page est redessinée à cette taille, si bien que les petits caractères restent nets ; le fond blanc la garde lisible même avec un thème sombre.

**Zoomer pour examiner une grande photo**
`Ctrl`+molette zoome **autour du curseur**. Les touches `+` `-` et les boutons du bas fonctionnent aussi. Faites glisser l'image agrandie pour la déplacer, et utilisez `Shift`+molette pour la déplacer latéralement. Quand l'image est plus grande que la fenêtre, le **navigateur** apparaît en bas à droite et encadre la zone affichée ; cliquez ou faites glisser pour y aller directement. En zoomant, l'original est relu, si bien que les détails fins restent nets.

**Masquer le navigateur**
Survolez le navigateur et cliquez sur le X qui apparaît. Pour le réafficher, activez **Paramètres → Affichage → Afficher le navigateur**.

**Changer le zoom rapidement**
`1` ajuster à la fenêtre, `2` taille réelle, `3` ajuster à la largeur, `4` ajuster à la hauteur. Le zoom choisi est conservé pour la page suivante et le prochain lancement : choisissez-le une fois pour toujours lire les scans larges à la largeur, ou toujours voir les photos en taille réelle.

**Consulter les informations de prise de vue**
Appuyez sur `Tab` pour afficher en haut à gauche le nom du fichier · la taille du fichier · la date de modification · les infos de l'image. Si la photo contient des données EXIF, la date de prise de vue · l'appareil · l'objectif · l'exposition · la focale · le flash · la position (GPS) s'affichent aussi — seules les lignes renseignées apparaissent. En mode deux pages, chaque page a ses propres infos sur sa moitié. Appuyez de nouveau sur `Tab` pour les masquer.

**Ouvrir des photos d'iPhone (HEIC), des RAW ou des fichiers Photoshop**
HEIC · AVIF · JPEG XL, les RAW de Canon · Nikon · Sony · Olympus · Pentax · Panasonic et les fichiers Photoshop PSD s'ouvrent comme n'importe quelle image en les déposant. Les photos s'ouvrent dans le sens où elles ont été prises, et les profils de couleur intégrés sont appliqués pour afficher leurs vraies couleurs.

**Regarder des GIF et WebP animés**
Ouvrez un GIF · APNG · WebP animé en mode une page et il se lance. Les modes deux pages et webtoon n'affichent que la première image.

**Trier ses photos en les regardant**
Appuyez sur `Delete` sur une photo dont vous ne voulez pas : une confirmation apparaît, et **Oui** l'envoie vers la Corbeille. Elle n'est pas effacée définitivement, vous pouvez la restaurer depuis la Corbeille. Si la confirmation vous gêne, désactivez **Paramètres → Général → Confirmer la suppression**. Cela ne concerne que les fichiers des dossiers ; les images à l'intérieur des archives ne sont pas touchées.

**Reprendre là où vous vous étiez arrêté**
Lancez simplement WorldView : la liste et la page que vous regardiez la dernière fois se rouvrent, et une BD inachevée reprend à cette page. Les 5 derniers éléments ouverts sont dans clic droit → **Fichiers récents**. Si vous préférez démarrer avec une fenêtre vide, désactivez **Rouvrir le dernier fichier au démarrage**.

**Profiter du plein écran**
Appuyez sur `Enter` ou cliquez sur `[]` dans la barre de titre pour un plein écran qui couvre aussi la barre des tâches. `Esc` ou `Enter` pour revenir. En plein écran, `Esc` ne quitte jamais le programme : il quitte seulement le plein écran.

**Garder la fenêtre au-dessus comme référence**
Cliquez sur la punaise de la barre de titre pour activer **Toujours au premier plan** : WorldView reste visible pendant que vous travaillez dans d'autres programmes — pratique pour dessiner d'après un modèle ou garder un document à côté de votre travail.

**Comparer deux images côte à côte**
Lancez un autre WorldView : la nouvelle fenêtre s'ouvre légèrement décalée pour ne pas recouvrir la première. Placez les fenêtres côte à côte pour comparer.

**Revenir au début après la dernière page**
Par défaut, aller au-delà de la dernière page s'arrête et affiche `C'est la dernière image`. Pour tourner en boucle comme un diaporama, réglez **Paramètres → Affichage → Au premier/dernier fichier** sur **Recommencer**.

**Ouvrir les images dans WorldView par double-clic**
Dans **Paramètres → Associations**, cochez les extensions à ouvrir avec WorldView (il y a aussi **Tout sélectionner**). Vous pouvez choisir JPG · PNG · GIF · WebP · TIFF · BMP · TGA · PSD · JPEG 2000 · DDS · PCX · PDF · CBZ · CBR, et les extensions d'un même format (`.jpg` `.jpeg` `.jfif`) partagent une seule case. Si **Non appliqué** apparaît à côté d'une case, Windows donne la priorité à un autre programme — cliquez sur cette mention pour ouvrir le choix de l'application par défaut pour cette extension et choisissez WorldView. La désinstallation de WorldView rétablit les associations d'origine.

**Adapter les raccourcis à vos habitudes**
Dans **Paramètres → Raccourcis**, cliquez sur la case de touche d'une action puis appuyez sur la nouvelle touche. Les combinaisons avec `Ctrl` · `Shift` · `Alt` fonctionnent. `Backspace` rétablit la valeur par défaut et `Esc` annule. Une touche déjà utilisée par une autre action est refusée, et l'action qui l'utilise est indiquée.

| Action | Touche par défaut |
|---|---|
| Ajuster à la fenêtre · Taille réelle · Ajuster à la largeur · Ajuster à la hauteur | `1` · `2` · `3` · `4` |
| Rotation de 90° dans le sens horaire | `R` |
| Afficher/masquer les infos de l'image | `Tab` |
| Basculer en plein écran | `Enter` |
| Ouvrir un fichier · Ouvrir un dossier | `O` · `Ctrl`+`O` |

Page précédente/suivante (`PageUp` `PageDown`), première/dernière page (`Home` `End`), agrandir/réduire (`+` `-`), Corbeille (`Delete`), ainsi que les flèches · `Space` · `Esc` sont fixes.

**Déplacer et redimensionner la fenêtre**
Faites glisser une zone vide autour de l'image, ou une image ajustée à la fenêtre, pour déplacer la fenêtre ; faites glisser un bord pour la redimensionner. Le glisser avec le bouton du milieu de la souris déplace aussi la fenêtre. La position et la taille de la fenêtre sont mémorisées, et elle s'ouvre au même endroit la fois suivante.

**Retrouver l'emplacement du fichier affiché**
Clic droit → **Afficher dans l'Explorateur** ouvre l'Explorateur avec ce fichier sélectionné — pratique pour le renommer ou le copier.

**Un écran plus épuré**
Dans **Paramètres → Affichage**, désactivez **Barres de défilement** et **Boutons fléchés latéraux** pour réduire ce qui s'affiche sur l'image. Vous pouvez toujours vous déplacer et tourner les pages de la même façon avec la molette · les flèches · le glisser.

## Configuration

Les changements faits dans **Paramètres**, ainsi que le zoom et le mode d'affichage choisis dans le menu Affichage, sont enregistrés automatiquement et réutilisés au prochain lancement.

| Élément | Par défaut |
|---|---|
| Zoom | Fenêtre |
| Affichage | Une page |
| Première page en couverture · Pages larges seules | Désactivé |
| Barres de défilement · Navigateur · Boutons fléchés latéraux · EXIF dans les infos | Activé |
| Au premier/dernier fichier | S'arrêter |
| Quitter avec Échap · Confirmer la suppression | Activé |
| Rouvrir le dernier fichier au démarrage | Activé |
| Toujours au premier plan · Journal | Désactivé |
| Langue | Système (suit le paramètre de région de Windows ; anglais si la langue n'est pas prise en charge) |

## Configuration requise

- Windows 10 · Windows 11 (64 bits)
- Tout ce qu'il faut pour ouvrir les images est inclus — rien d'autre à installer. Aucun droit d'administrateur n'est nécessaire pour l'exécuter.
- La connexion Internet ne sert qu'aux avis de nouvelle version. Toutes les images sont ouvertes sur votre PC.

## Mises à jour

WorldView ne se met **pas** à jour tout seul. Au démarrage, il vérifie s'il existe une nouvelle version et affiche un avis ; cliquer sur **[Oui]** ouvre la page de téléchargement et ferme le programme. Les nouvelles versions sont publiées manuellement après des tests internes et annoncées sur la [page de WorldView](https://kilho.net/worldview). Consultez l'[avis sur la politique de mise à jour](https://en.kilho.net/archives/notice/2940).

## Licence

WorldView est un **gratuiciel**. Vous pouvez l'utiliser gratuitement et sans restriction partout — au bureau, à la maison, dans les administrations ou à l'école — et le redistribuer librement.

## Liens

- Site web : <https://kilho.net/worldview>
- Forum : <https://kilho.top/forum/qna>
- X (Twitter) : <https://www.twitter.com/kilhonet>

© KILHO.NET
