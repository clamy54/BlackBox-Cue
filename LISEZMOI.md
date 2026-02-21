# BlackBox Cue

Un lecteur de cues audio gratuit pour le théâtre, les spectacles vivants et les événements scéniques. Également idéal pour tout lieu nécessitant une musique d'ambiance : salles d'attente, commerces, restaurants, expositions, etc. La précision sans la complexité.

![BlackBox Cue](screenshot.png)

---

## Pourquoi BlackBox Cue ?

BlackBox Cue est conçu pour une **utilisation live et réactive**. Contrairement aux logiciels de conduite traditionnels qui nécessitent une longue pré-programmation, BlackBox Cue fonctionne comme une **palette sonore** : tous vos fichiers audio sont disposés sur des pads, prêts à être déclenchés instantanément d'un simple clic.

Pas de configuration complexe, pas de programmation, pas de courbe d'apprentissage. Importez vos fichiers et c'est parti.

### Pour qui ?

- **Régisseurs live** -- Calez directement les musiques pendant la répétition.Pas de temps de préparation : assignez un fichier, réglez le comportement, lancez.
- **Spectacles d'improvisation** -- Rien n'est écrit. Le régisseur son réagit en temps réel avec 108 sons sous la main.
- **Artistes solo** -- One-man show, magiciens, conteurs : gérez vos bandes son en autonomie avec une télécommande sans fil ou un Stream Deck, sans ingénieur son.
- **Écoles de danse et chorégraphes** -- Lancez, arrêtez et enchaînez les musiques instantanément avec le crossfade. L'Auto-Trim saute le silence pour que vos cues démarrent pile sur le temps.
- **Compagnies et ateliers** -- Préparez une conduite efficace en quelques minutes, pas en plusieurs heures. Chaque pad a son propre comportement de fin (one-shot, boucle, continue), de début (auto-trim, offset personnalisé) et ses réglages de fondu.
- **Spectacles jeune public** -- Le timing dépend des réactions du public. Déclenchez n'importe quel son à n'importe quel moment, dans n'importe quel ordre.
- **Musique d'ambiance** -- Salles d'attente, commerces, restaurants, expositions : configurez une playlist avec le mode Continue et le crossfade, et laissez tourner.

### La précision sans la complexité

BlackBox Cue vous donne les outils essentiels pour la diffusion live, sans la lourdeur d'un système de conduite complet :

- **Auto-Trim** : détecte et saute automatiquement les silences au début et à la fin de chaque piste. Vos cues démarrent et s'arrêtent exactement sur le son.
- **Temps restant** : toujours visible pendant la lecture, pour savoir précisément combien de temps il reste avant la prochaine cue.
- **Fade-in et fade-out par piste** : durée réglable de 0 à 10 secondes pour des transitions en douceur.
- **Comportement de fin par piste** : one-shot, boucle ou enchaînement vers le pad suivant -- configuré une fois, fiable à chaque représentation.
- **Crossfade equal-power** entre les pistes pour des transitions fluides.
- **Normalisation du volume** : équilibre automatiquement toutes vos pistes à un volume perçu homogène, même quand les fichiers proviennent de sources différentes.
- **Forme d'onde** en mode édition : visualisez précisément où commence et se termine votre audio, et où se situent les points de trim.

---

## Prise en main

### Installation

1. Téléchargez la dernière version
2. Lancez l'installateur
3. Démarrez BlackBox Cue

### Configuration requise

- Windows 10 ou 11 (64 bits)
- Un périphérique de sortie audio

---

## Votre premier projet

### Créer un nouveau projet

1. Cliquez sur le bouton **New**
2. Choisissez un dossier où votre projet sera enregistré
3. Un fichier projet `.bbc` et un dossier `imports` sont créés automatiquement

Le dossier `imports` est l'endroit où tous vos fichiers audio seront stockés.

**Important :** Ne placez pas deux fichiers `.bbc` dans le même dossier. Le dossier `imports` étant créé au même niveau que le fichier `.bbc`, deux projets dans le même dossier partageraient les mêmes fichiers audio, ce qui peut prêter à confusion.

**Remarque :** Vous devez créer un nouveau projet ou en ouvrir un existant avant de pouvoir travailler avec les pads.

### Ouvrir un projet existant

Cliquez sur le bouton **Open Project** et sélectionnez un fichier `.bbc`.

### Sauvegarde et transfert

Pour sauvegarder ou transférer un projet vers un autre ordinateur, il suffit de copier le fichier `.bbc` et le dossier `imports` situé dans le même répertoire. Pour restaurer ou importer un projet, copiez ces deux éléments — le dossier `imports` doit se trouver dans le même répertoire que le fichier `.bbc`.

---

## Importer des fichiers audio

BlackBox Cue prend en charge les fichiers audio **WAV**, **MP3** et **AIFF**.

Les fichiers AIFF sont automatiquement convertis au format WAV lors de l'importation.

### Importer un fichier

1. Cliquez sur le bouton **Import**
2. Sélectionnez un fichier audio sur votre ordinateur
3. Donnez-lui un nom (ou conservez l'original)
4. Pour les fichiers WAV et MP3, le fichier est copié dans le dossier `imports` de votre projet. La copie est sécurisée : l'intégrité du fichier de destination est vérifiée par rapport au fichier source pour garantir qu'aucune donnée n'a été perdue ou corrompue
5. Pour les fichiers AIFF, le fichier est converti au format WAV et enregistré dans le dossier `imports` de votre projet

### Auto-Assign (importation en masse)

Pour remplir tous les pads d'un coup :

1. Cliquez sur "Switch to crossfade mode"
2. Cliquez sur le bouton **Auto-Assign**
3. Sélectionnez un dossier contenant vos fichiers audio (les sous-dossiers sont inclus)
4. Confirmez l'opération (cela effacera tous les pads existants)
5. Les fichiers sont automatiquement copiés, assignés aux pads et nommés

Si le dossier contient plus de 108 fichiers, 108 fichiers sont choisis aléatoirement. Chaque Auto-Assign produit ainsi une playlist différente, idéal pour renouveler la musique d'ambiance.

Utile pour préparer rapidement un spectacle avec de nombreuses cues sonores.

---

## Pads

BlackBox Cue vous offre **108 pads** organisés sur **9 pages** de 12 pads chacune.

Chaque pad peut contenir un fichier audio et possède ses propres réglages de lecture.

### Jouer un pad

Cliquez simplement sur un pad pour le lancer. Le pad s'allume en vert pendant la lecture.

### Naviguer entre les pages

- Utilisez les boutons **Page Up** et **Page Down** pour changer de page
- Le numéro de la page courante est affiché en haut de l'écran

---

## Mode édition

Pour configurer un pad, passez en **Mode édition** en cliquant sur le bouton **Edit**.

En mode édition, cliquer sur un pad le sélectionne pour l'édition (il s'allume en jaune). Vous pouvez alors :

- **Assigner un fichier audio** avec le bouton Browse
- **Définir un nom** (le texte affiché sur le pad, 14 caractères maximum)
- **Choisir un comportement de fin** (ce qui se passe quand la piste se termine)
- **Choisir un comportement de début** (où la lecture commence)
- **Sauvegarder**

### Comportement de fin

- **One-Shot** : la piste est jouée une fois puis s'arrête
- **Loop** : la piste se répète indéfiniment (idéal pour les ambiances sonores ou les boucles musicales)
- **Continue** : quand la piste se termine, le pad suivant se lance automatiquement (idéal pour les conduites séquentielles). En mode crossfade, lorsque le dernier pad (108) se termine, la lecture reprend automatiquement au pad 1

### Comportement de début

- **Start from zero** : la lecture commence au tout début du fichier
- **Auto-Trim** : la lecture saute les silences au début et à la fin du fichier (détectés automatiquement). Remarque : l'Auto-Trim ne fonctionne que si le silence ne dépasse pas 10 secondes. Au-delà de 10 secondes, le silence est considéré comme intentionnel et fait partie intégrante du morceau, il sera donc joué normalement
- **Custom offset** : la lecture commence à un moment que vous choisissez, ajustable avec les boutons +/-

### Affichage de la forme d'onde

En mode édition, la forme d'onde du fichier audio est affichée. Cliquez sur la forme d'onde pour basculer entre la vue du **début** et de la **fin** de la piste.

Une ligne jaune indique le point de début Auto-Trim. Une ligne orange indique le point de fin Auto-Trim. Une ligne cyan indique votre offset de début personnalisé.

---

## Contrôles de lecture

### Stop

Cliquez sur le bouton **Stop** pour arrêter toute lecture en cours, y compris les SFX.

- Si un fade-out est configuré, la première pression lance le fade-out
- Appuyez à nouveau pendant le fade pour arrêter immédiatement

### Pause / Reprise

Cliquez sur le bouton **Pause** pour mettre la lecture en pause. Cliquez à nouveau pour reprendre. L'affichage du temps clignote pendant la pause.

### Recherche

Cliquez sur la barre de progression pour sauter à n'importe quelle position dans la piste.

---

## Contrôles de fondu

### Fade-In

Définissez la durée d'une montée progressive du volume au lancement d'une piste. Réglable de 0 à 10 secondes.

- Cliquez sur **+** ou **-** pour ajuster par pas de 0,2 seconde
- Maintenez **Shift** et cliquez pour ajuster par pas de 1 seconde
- Maintenez le bouton enfoncé pour la répétition automatique

### Fade-Out

Définissez la durée d'une descente progressive du volume quand vous appuyez sur Stop. Réglable de 0 à 10 secondes. Mêmes contrôles que le Fade-In.

### Crossfade

Activez la case **Crossfade** pour enchaîner les pistes en douceur. Quand vous lancez un nouveau pad pendant qu'un autre joue, l'ancienne piste descend en volume tandis que la nouvelle monte simultanément. La durée du crossfade est réglable de 1 à 10 secondes.

---

## Pads SFX

En plus des 108 pads principaux, BlackBox Cue propose **2 pads SFX dédiés** (SFX 1 et SFX 2) pour les effets sonores.

Les pads SFX se jouent **indépendamment** de la lecture principale : vous pouvez déclencher un ou deux SFX pendant qu'un pad principal joue, sans l'interrompre. Les deux pads SFX peuvent aussi jouer simultanément.

Les pads SFX sont toujours en mode **one-shot** (pas de boucle, pas de continue). Ils disposent de leur propre **curseur de volume** (0–130%), indépendant du fader principal. Cela permet de régler un niveau fixe pour vos effets sonores, quel que soit le volume de sortie principal. Les valeurs au-dessus de 100% permettent d'amplifier les effets sonores les plus discrets.

Pour configurer un pad SFX, passez en mode édition et cliquez sur le bouton SFX 1 ou SFX 2. Vous pouvez assigner un fichier audio, choisir un comportement de début et régler le niveau de volume.

---

## Volume

Utilisez le **fader de volume** vertical sur le côté droit de l'écran pour ajuster le volume de sortie. Glissez vers le haut pour augmenter, vers le bas pour diminuer.

### Normalisation du volume

Activez la case **Normalize** pour équilibrer automatiquement le volume de toutes vos pistes. Les fichiers audio sont souvent enregistrés à des niveaux différents, ce qui peut provoquer des sauts de volume désagréables en passant d'un pad à l'autre.

Quand la normalisation est activée, BlackBox Cue analyse le niveau de chaque fichier audio et ajuste le gain de lecture pour que toutes les pistes soient perçues à un volume cohérent.

---

## VU-mètre

Le VU-mètre à LEDs affiche le niveau de sortie audio en temps réel, avec un indicateur de crête.

---

## Affichage

Pendant la lecture, l'écran affiche :

- **Nom de la piste** : le nom du fichier audio en cours
- **Temps écoulé** : depuis combien de temps la piste joue
- **Temps restant** : combien de temps il reste
- **Mode de lecture** : LOOP, ONE-SHOT ou CONTINUE

---

## Télécommande sans fil

BlackBox Cue est compatible avec les télécommandes de présentation sans fil (du type utilisé pour les présentations PowerPoint).

Activez la case **Remote**, puis utilisez votre télécommande pour contrôler la lecture en mains libres :

| Bouton | Action |
|--------|--------|
| Volume Down | Lancer le pad sélectionné |
| Volume Up (appui court) | Arrêter la lecture |
| Volume Up (appui long >2s) | Avancer au pad suivant |
| Page Down | Sélectionner le pad suivant |
| Page Up | Sélectionner le pad précédent |
| Touche B | Arrêter la lecture et avancer au pad suivant |

Le pad sélectionné est mis en surbrillance à l'écran. La navigation change automatiquement de page si nécessaire.

---

## Raccourcis clavier

BlackBox Cue propose des raccourcis clavier pour un contrôle rapide de la lecture (actifs en dehors du mode édition) :

| Touche | Action |
|--------|--------|
| F1 – F12 | Jouer le pad 1–12 de la page courante |
| 1 | Jouer SFX 1 |
| 2 | Jouer SFX 2 |
| Espace | Arrêter la lecture |
| Page Up | Page précédente |
| Page Down | Page suivante |

Ces raccourcis sont désactivés lors de la saisie dans un champ texte ou quand une boîte de dialogue est ouverte.

---

## Support Stream Deck

BlackBox Cue prend en charge le **Stream Deck Elgato** (modèle 15 touches) comme surface de contrôle physique.

![Stream Deck](streamdeck.jpg)

### Détection automatique

Lorsqu'un projet est ouvert, BlackBox Cue vérifie la présence d'un Stream Deck connecté. Lorsqu'il est détecté, la case **Enable Stream Deck** et son libellé apparaissent. Si le Stream Deck est débranché, l'affichage revient automatiquement à « STREAM DECK NOT DETECTED ».

**Important :** Le logiciel Elgato Stream Deck doit être fermé avant d'activer le Stream Deck dans BlackBox Cue afin d'éviter les interactions indésirables entre les deux logiciels.

### Disposition des touches

Les 15 touches sont organisées comme suit :

| | Col 1 | Col 2 | Col 3 | Col 4 | Col 5 |
|---|---|---|---|---|---|
| Ligne 1 | Pad 1 | Pad 2 | Pad 3 | Pad 4 | **STOP** |
| Ligne 2 | Pad 5 | Pad 6 | Pad 7 | Pad 8 | **PAUSE** |
| Ligne 3 | Pad 9 | Pad 10 | Pad 11 | Pad 12 | **PAGE** |

- Les touches de pad affichent le **numéro du pad** (en noir, en haut) et le **caption** (en blanc, en dessous)
- Le pad en cours de lecture est affiché en **vert** avec une **barre de progression**
- Les pads vides sont affichés en gris

### Modes SFX et Page

La touche en bas à droite permet de basculer entre trois modes : **Normal → SFX → Page → Normal**.

| Touche | Normal | Mode SFX | Mode Page |
|--------|--------|----------|-----------|
| Touche 5 (haut droite) | STOP | SFX 1 | P+ (page suivante) |
| Touche 10 (milieu droite) | PAUSE | SFX 2 | P- (page précédente) |
| Touche 15 (bas droite) | SFX | PAGE | RETURN |

---

## Astuces

- **Anti-veille** : BlackBox Cue empêche automatiquement votre ordinateur de se mettre en veille ou d'éteindre l'écran tant que l'application est en cours d'exécution, pour que votre spectacle ne soit pas interrompu.
- **Mode Continue** : Utilisez le mode Continue sur tous vos pads pour créer une playlist automatique qui enchaîne toute votre conduite.
- **Crossfade + Continue** : Combinez le crossfade avec le mode Continue pour des transitions fluides entre les pistes.
- **Auto-Trim** : La plupart des fichiers audio ont un court silence au début. L'Auto-Trim le détecte et le saute, pour que vos cues démarrent directement sur le son. Les silences de plus de 10 secondes en début ou en fin de piste sont considérés comme intentionnels et ne seront pas pris en compte par l'auto-trim.

---

## Démarrage rapide : playlist d'ambiance

Mettre en place une playlist musicale pour une salle d'attente, un restaurant ou une exposition prend moins d'une minute :

1. Créez un nouveau projet
2. Passez en mode crossfade
3. Cliquez sur le bouton **Auto-Assign** et sélectionnez un répertoire contenant vos fichiers musicaux. Si le répertoire contient plus de 108 fichiers, 108 fichiers seront importés aléatoirement. La lecture bouclera automatiquement une fois le dernier pad joué
4. Cliquez sur le bouton **Norm** sous le fader de volume pour activer la normalisation
5. Réglez le volume de sortie au niveau souhaité
6. Réglez le crossfade à environ 5 secondes pour des transitions en douceur
7. Lancez la lecture du premier pad

C'est tout -- votre playlist tourne toute seule avec des enchaînements fluides entre les pistes.

**Astuce :** Si vous importez un jingle (fonction Import) en mode Continue, vous pouvez ensuite assigner ce même jingle à plusieurs pads sur des pages différentes. Cela permet d'intégrer un jingle à différents endroits de la playlist. On peut faire de même avec des spots publicitaires.

---

## Licence

Copyright (c) 2025 Cyril LAMY. Tous droits réservés.

Ce logiciel est un **FREEWARE**. Vous pouvez l'utiliser et le distribuer librement à des fins personnelles ou commerciales.

**AVERTISSEMENT :** Ce logiciel est fourni « en l'état », sans garantie d'aucune sorte. L'auteur ne pourra être tenu responsable de tout dommage ou préjudice découlant de l'utilisation de ce logiciel.

---
