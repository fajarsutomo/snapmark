# Guide d'utilisation de SnapMark

SnapMark capture l'écran de Windows et vous permet de l'annoter avec des marques qui **restent modifiables** : rectangles, flèches, texte, masquages et plus encore sont des objets distincts, et non des pixels peints sur l'image. L'image d'origine n'est jamais modifiée.

[Autres langues / Other languages](../README.md)

## Sommaire

1. [Installation](#installation)
2. [Capturer l'écran](#capturer-lécran)
3. [Outils d'annotation](#outils-dannotation)
4. [Raccourcis clavier](#raccourcis-clavier)
5. [Copier et enregistrer](#copier-et-enregistrer)
6. [Projets et historique](#projets-et-historique)
7. [Paramètres](#paramètres)
8. [Confidentialité](#confidentialité)
9. [Dépannage](#dépannage)

## Installation

Lancez le programme d'installation `SnapMark_x.y.z_x64-setup.exe`. Il s'installe uniquement pour votre compte (aucun droit d'administrateur requis). SnapMark s'exécute ensuite dans la **zone de notification** (près de l'horloge). Si l'icône est invisible, cliquez sur la flèche ^ pour afficher les icônes masquées.

Faites un clic droit sur l'icône pour ouvrir le menu : **Capturer**, **Historique**, **Ouvrir un projet…**, **Paramètres**, **Quitter**.

## Capturer l'écran

1. Appuyez sur **Impr. écran** (ou cliquez sur l'icône de la zone de notification, ou choisissez **Capturer**). L'écran se fige un instant ; avec plusieurs écrans, tous sont capturés.
2. **Faites glisser** pour choisir une zone. Vous pouvez la modifier à tout moment, même après avoir ajouté des annotations : faites glisser son **contour** pour la déplacer, une **poignée** de coin ou de côté pour la redimensionner, ou faites glisser dans la zone sombre extérieure pour choisir de nouveau. Les flèches du clavier déplacent la zone ; **Ctrl + flèche** la redimensionne ; **Maj** fait avancer par pas de 10 pixels.
3. Utilisez la barre d'outils pour ajouter des annotations.
4. Appuyez sur **Entrée** pour copier dans le presse-papiers, ou sur **Ctrl+S** pour enregistrer. **Échap** annule.

Le premier Échap désélectionne les objets ; le suivant ferme SnapMark.

## Outils d'annotation

| Outil | Touche | Remarques |
|---|---|---|
| Sélectionner et modifier | `V` | Cliquez sur un objet pour le sélectionner ; **Maj+clic** ajoute ou retire de la sélection. Faites glisser pour déplacer, tirez une poignée pour redimensionner. |
| Rectangle | `R` | **Maj** = carré. Peut être rempli. |
| Ellipse | `E` | **Maj** = cercle. |
| Ligne | `L` | **Maj** = angles de 45°. Styles : pleine, double, pointillée. |
| Flèche | `A` | **Maj** = 45°. Pointe à une ou aux deux extrémités. |
| Crayon libre | `P` | Dessin à main levée. |
| Surligneur | `H` | Marqueur translucide. |
| Masquer | `S` | Mosaïque, flou ou **bloc noir** (le plus sûr). Forme rectangulaire ou pinceau. |
| Numéro d'étape | `N` | Cliquez pour placer 1, 2, 3… dans l'ordre. |
| Texte | `T` | Fond au choix. **Ctrl+Entrée** ou **Échap** termine. |

La couleur, l'épaisseur, la taille de police et le gras se règlent dans la barre d'outils ; les changements s'appliquent aux objets sélectionnés.

## Raccourcis clavier

| Touche | Action |
|---|---|
| `Entrée` / `Ctrl+C` | Copier le résultat dans le presse-papiers |
| `Ctrl+S` | Enregistrer le PNG dans le dossier d'enregistrement |
| `Ctrl+Maj+S` | Enregistrer sous… |
| `Ctrl+Alt+S` | Enregistrer un projet `.snapmark` |
| `Ctrl+Z` / `Ctrl+Y` (ou `Ctrl+Maj+Z`) | Annuler / rétablir |
| `Ctrl+D` | Dupliquer les objets sélectionnés |
| `Ctrl+A` | Sélectionner tous les objets |
| `Ctrl+]` / `Ctrl+[` | Premier plan / arrière-plan |
| `Suppr` / `Retour arrière` | Supprimer les objets sélectionnés |
| Flèches (`Maj` = 10 px) | Déplacer les objets sélectionnés ; sans sélection, déplacer la zone (avec `Ctrl` : la redimensionner) |
| `Échap` | Désélectionner, puis fermer |

## Copier et enregistrer

Le résultat est toujours **uniquement la zone sélectionnée**, à la **résolution d'origine** de l'écran, exactement comme vous la voyez.

- **Copier** (Entrée) : va dans le presse-papiers, prêt à coller.
- **Enregistrer** (Ctrl+S) : directement dans le dossier d'enregistrement sous le nom `snapmark_20261125_143005.png` (date_heure). Un fichier existant n'est jamais écrasé (un suffixe `_2`, `_3`, … est ajouté). Dossier par défaut : `Images\SnapMark`.
- **Enregistrer sous** (Ctrl+Maj+S) : choisissez vous-même le nom et le dossier.

Après une copie ou un enregistrement réussi, SnapMark se ferme automatiquement.

## Projets et historique

Un **projet `.snapmark`** conserve l'image d'origine et chaque annotation sous forme d'objet, afin de pouvoir le rouvrir et le modifier plus tard. Enregistrez avec **Ctrl+Alt+S** ; ouvrez-le par un double-clic sur le fichier ou via la zone de notification → **Ouvrir un projet…**.

> **Attention aux masquages.** Le fichier de projet conservant l'image *d'origine*, tout ce que vous avez masqué reste visible pour quiconque ouvre ce fichier. Pour partager, utilisez **Copier** ou **Enregistrer le PNG**, qui ne contiennent que le résultat masqué. SnapMark vous avertit avant d'enregistrer un projet contenant un masquage.

**Historique** : chaque Copier/Enregistrer est consigné automatiquement comme projet modifiable (les 50 derniers par défaut, uniquement sur cet ordinateur). Ouvrez-le via la zone de notification → **Historique** et cliquez sur un élément pour le modifier de nouveau.

## Paramètres

Zone de notification → **Paramètres**.

| Paramètre | Description |
|---|---|
| Raccourci de capture | `Impr. écran` par défaut. Cliquez sur **Modifier…** puis appuyez sur la nouvelle combinaison (avec Ctrl/Alt/Win pour ne pas gêner la saisie). |
| Dossier d'enregistrement | Destination de Ctrl+S. |
| Langue | Bahasa Indonesia, English, Español, Deutsch, 日本語, 简体中文, Français, Italiano, Português (Brasil), 한국어, Русский, العربية, Nederlands, ou comme Windows. |
| Historique | Nombre d'éléments conservés (0 = désactivé, 500 au maximum). |
| Démarrer avec Windows | SnapMark est prêt dès l'ouverture de session. |
| Couleur de l'aide | Couleur du texte d'instructions pendant le choix d'une zone. |
| Thème | Comme Windows, Clair, Sombre ou Liquid Glass. |
| Mises à jour | Recherche et installation automatiques toutes les 6 heures, ou bouton **Vérifier maintenant**. |

Les mises à jour sont téléchargées depuis la version officielle, installées sans fenêtre d'installation, et SnapMark se rouvre tout seul ; vos paramètres et votre historique sont conservés. Une mise à jour attend que vous ayez fini de modifier.

## Confidentialité

- Les captures et les projets **ne quittent jamais votre ordinateur**.
- Aucune télémétrie. Le seul accès réseau est la recherche de mises à jour.

## Dépannage

**Impr. écran ne fait rien / le raccourci n'est pas actif.** Windows 11 peut réserver cette touche à son propre outil de capture. Dans les Paramètres de SnapMark, cliquez sur **Ouvrir les paramètres du clavier Windows**, puis désactivez l'option qui fait ouvrir cet outil par la touche Impr. écran (son nom et son emplacement varient selon la version de Windows). Ou choisissez un autre raccourci.

**L'icône de la zone de notification est absente.** Cliquez sur la flèche ^ de la barre des tâches ; faites glisser l'icône SnapMark vers l'extérieur pour qu'elle reste toujours visible.

**Emplacement des données.** Paramètres : `%APPDATA%\app.snapmark.desktop\settings.json`. Historique : `%LOCALAPPDATA%\app.snapmark.desktop\history`.
