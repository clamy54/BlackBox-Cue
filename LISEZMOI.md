# BlackBox Cue

Un lecteur de cues audio simple et puissant pour le théâtre, les spectacles vivants et les événements scéniques. Également idéal pour tout lieu nécessitant une musique d'ambiance : salles d'attente, commerces, restaurants, expositions, etc.

![BlackBox Cue](screenshot.png)

---

## Pourquoi BlackBox Cue ?

BlackBox Cue est conçu pour une **utilisation live et réactive**. Contrairement aux logiciels de conduite traditionnels qui nécessitent une longue pré-programmation, BlackBox Cue fonctionne comme une **palette sonore** : tous vos fichiers audio sont disposés sur des pads, prêts à être déclenchés instantanément d'un simple clic.

C'est l'outil idéal pour :

- **Les répétitions de théâtre** où le metteur en scène essaie différents sons à la volée et où le timing change constamment
- **Les spectacles d'improvisation** où rien n'est écrit et où le régisseur son réagit en temps réel
- **Les répétitions de danse** où la musique doit être lancée, arrêtée et changée rapidement
- **Les spectacles jeune public** où le timing dépend des réactions du public
- **Toute situation live** où il faut s'adapter sur le moment plutôt que suivre une séquence figée

Pas de configuration complexe, pas de programmation, pas de courbe d'apprentissage. Importez vos fichiers et c'est parti.

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
3. Un fichier projet `.bbcue` et un dossier `imports` sont créés automatiquement

Le dossier `imports` est l'endroit où tous vos fichiers audio seront stockés.

**Remarque :** Vous devez créer un nouveau projet ou en ouvrir un existant avant de pouvoir travailler avec les pads.

### Ouvrir un projet existant

Cliquez sur le bouton **Open Project** et sélectionnez un fichier `.bbcue`.

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
- **Continue** : quand la piste se termine, le pad suivant se lance automatiquement (idéal pour les conduites séquentielles)

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

Cliquez sur le bouton **Stop** pour arrêter la lecture.

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

## Volume

Utilisez le **fader de volume** vertical sur le côté droit de l'écran pour ajuster le volume de sortie. Glissez vers le haut pour augmenter, vers le bas pour diminuer.

### Normalisation du volume

Activez la case **Normalize** pour équilibrer automatiquement le volume de toutes vos pistes. Les fichiers audio sont souvent enregistrés à des niveaux différents, ce qui peut provoquer des sauts de volume désagréables en passant d'un pad à l'autre.

Quand la normalisation est activée, BlackBox Cue analyse le niveau RMS de chaque fichier audio et ajuste le gain de lecture pour que toutes les pistes soient perçues à un volume cohérent.

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

Le pad sélectionné est mis en surbrillance à l'écran. La navigation change automatiquement de page si nécessaire (dans les deux sens).

---

## Astuces

- **Anti-veille** : BlackBox Cue empêche automatiquement votre ordinateur de se mettre en veille ou d'éteindre l'écran tant que l'application est en cours d'exécution, pour que votre spectacle ne soit pas interrompu.
- **Mode Continue** : Utilisez le mode Continue sur tous vos pads pour créer une playlist automatique qui enchaîne toute votre conduite.
- **Crossfade + Continue** : Combinez le crossfade avec le mode Continue pour des transitions fluides entre les pistes.
- **Auto-Trim** : La plupart des fichiers audio ont un court silence au début. L'Auto-Trim le détecte et le saute, pour que vos cues démarrent directement sur le son. Les silences de plus de 10 secondes sont considérés comme intentionnels et ne seront pas supprimés.

---

## Licence

Copyright (c) 2025 Cyril LAMY. Tous droits réservés.

Ce logiciel est un **FREEWARE**. Vous pouvez l'utiliser et le distribuer librement à des fins personnelles ou commerciales.

**AVERTISSEMENT :** Ce logiciel est fourni « en l'état », sans garantie d'aucune sorte. L'auteur ne pourra être tenu responsable de tout dommage ou préjudice découlant de l'utilisation de ce logiciel.

---
