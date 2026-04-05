# BlackBox Cue

Un lecteur de cues audio gratuit pour le théâtre, les spectacles vivants et les événements scéniques. Également idéal pour tout lieu nécessitant une musique d'ambiance : salles d'attente, commerces, restaurants, expositions, etc.

**En raison de la taille des installeurs, BlackBox Cue n'est plus disponible en téléchargement sur GitHub. Ce dépôt contient uniquement la documentation. BlackBox Cue est un logiciel gratuit : téléchargez-le sur le site officiel : https://www.blackboxcue.net/**

![BlackBox Cue](screenshot.png)

---

## Pourquoi BlackBox Cue ?

Toutes les régies n'ont pas besoin d'une timeline verrouillée. La plupart ont surtout besoin de réagir vite, de lancer le bon son au bon moment, d'enchaîner proprement et de garder la maîtrise en situation réelle. Théâtre, danse, impro, jeune public, solo, événementiel, ambiance : sur le terrain, la régie est souvent plus vivante que programmée. BlackBox Cue a été conçu pour cette réalité.

BlackBox Cue fonctionne comme une **palette sonore** : tous vos fichiers audio sont disposés sur des pads, prêts à être déclenchés instantanément d'un simple clic. Pas de configuration complexe, pas de programmation, pas de courbe d'apprentissage. Importez vos fichiers et c'est parti.

### Pour qui ?

- **Régisseurs live**. Calez directement les musiques pendant la répétition.Pas de temps de préparation : assignez un fichier, réglez le comportement, lancez.
- **Spectacles d'improvisation**. Rien n'est écrit. Le régisseur son réagit en temps réel avec 300 sons sous la main.
- **Artistes solo**. One-man show, magiciens, conteurs : gérez vos bandes son en autonomie avec une télécommande sans fil ou un Stream Deck, sans ingénieur son.
- **Écoles de danse et chorégraphes**. Lancez, arrêtez et enchaînez les musiques instantanément avec le crossfade. L'Auto-Trim saute le silence pour que vos cues démarrent pile sur le temps. Le contrôle de vitesse permet de ralentir la musique pour l'apprentissage d'une chorégraphie, puis de la jouer à vitesse normale pour le spectacle.
- **Compagnies et ateliers**. Préparez une conduite efficace en quelques minutes, pas en plusieurs heures. Chaque pad a son propre comportement de fin (one-shot, boucle, continue), de début (auto-trim, offset personnalisé) et ses réglages de fondu.
- **Spectacles jeune public**. Le timing dépend des réactions du public. Déclenchez n'importe quel son à n'importe quel moment, dans n'importe quel ordre.
- **Musique d'ambiance**. Salles d'attente, commerces, restaurants, expositions : configurez une playlist avec le mode Continue et le crossfade, et laissez tourner.

### La précision sans la complexité

BlackBox Cue vous donne les outils essentiels pour la diffusion live, sans la lourdeur d'un système de conduite complet :

- **Auto-Trim** : détecte et saute automatiquement les silences au début et à la fin de chaque piste. Vos cues démarrent et s'arrêtent exactement sur le son.
- **Temps restant** : toujours visible pendant la lecture, pour savoir précisément combien de temps il reste avant la prochaine cue.
- **Fade-in et fade-out par piste** : durée réglable de 0 à 10 secondes pour des transitions en douceur.
- **Comportement de fin par piste** : one-shot, boucle ou enchaînement vers le pad suivant: configuré une fois, fiable à chaque représentation.
- **Crossfade equal-power** entre les pistes pour des transitions fluides. En mode AUTO, le crossfade analyse votre musique et trouve automatiquement le meilleur moment pour enchaîner, en s'adaptant au tempo, à la tonalité et à la structure de chaque morceau.
- **Sélection de la sortie audio** : choisissez quel périphérique audio utiliser, directement depuis l'interface principale.
- **Préécoute** en mode édition : écoutez les premières secondes d'un morceau sur une sortie audio séparée avant de le diffuser en live. Nécessite un ordinateur disposant d'au moins deux sorties audio indépendantes.
- **Égaliseur paramétrique 4 bandes par pad**, avec bandes Low, Low Mid, High Mid et High. Chaque bande propose plusieurs modes de filtre (PEQ, VEQ, Low Cut, High Cut, Low Shelf, High Shelf) avec fréquence, gain et Q réglables. Un graphique de réponse fréquentielle et un spectrogramme temps réel permettent de visualiser l'effet de vos réglages pendant la préécoute.
- **Égaliseur général** avec le même égaliseur paramétrique 4 bandes, appliqué à l'ensemble de la sortie audio. Idéal pour s'adapter à l'acoustique de la salle. Inclut un spectrogramme temps réel de la sortie principale.
- **Effets audio par pad** : appliquez une réverbération, un delay, un flanger, un lo-fi, un effet robot, une distorsion ou un vocal remover sur n'importe quel pad. Chaque type d'effet propose des presets prêts à l'emploi et un simple contrôle de dosage (wet/dry). Les effets sont conservés pendant les transitions crossfade.
- **Contrôle de vitesse par pad** : ajustez la vitesse de lecture de 50% à 120% sans modifier la hauteur du son. Idéal pour les écoles de danse qui ont besoin de ralentir la musique pour l'apprentissage d'une chorégraphie, puis de la jouer à pleine vitesse pour le spectacle.
- **Normalisation du volume** : équilibre automatiquement toutes vos pistes à un volume perçu homogène, même quand les fichiers proviennent de sources différentes.
- **Forme d'onde** en mode édition : visualisez précisément où commence et se termine votre audio, et où se situent les points de trim.

---

## Prise en main

### Installation

**Windows :**

1. Téléchargez la dernière version au format zip depuis le site officiel et décompressez le fichier
2. Lancez l'installateur
3. Démarrez BlackBox Cue

**macOS (Apple Silicon) :**

1. Téléchargez le fichier `.dmg` depuis le site officiel
2. Ouvrez le `.dmg` et glissez BlackBox Cue dans votre dossier Applications
3. Démarrez BlackBox Cue

### Configuration requise

- Windows 10 ou 11 (64 bits), ou macOS 11+ sur un Mac avec puce Apple Silicon
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

Pour sauvegarder ou transférer un projet vers un autre ordinateur, il suffit de copier le fichier `.bbc` et le dossier `imports` situé dans le même répertoire. Pour restaurer ou importer un projet, copiez ces deux éléments - le dossier `imports` doit se trouver dans le même répertoire que le fichier `.bbc`.

---

## Importer des fichiers audio

BlackBox Cue prend en charge de nombreux formats audio : **WAV**, **MP3**, **OGG**, **FLAC**, **AAC/M4A**, **MP4**, **AIFF**, **ALAC**, **WMA**, **Opus**, **CAF**, **AC-3**, **WavPack**, **MKA** (Matroska Audio), **AU** et **SND**.

### Importer un fichier

1. Cliquez sur le bouton **Import**
2. Sélectionnez un fichier audio sur votre ordinateur
3. Donnez-lui un nom (ou conservez l'original)
4. Le fichier est copié dans le dossier `imports` de votre projet. La copie est sécurisée : l'intégrité du fichier de destination est vérifiée par rapport au fichier source pour garantir qu'aucune donnée n'a été perdue ou corrompue

### Importer un dossier

Faites un **clic droit** sur le bouton **Import** pour le basculer en mode **IMPORT DIR**. Dans ce mode, un clic sur le bouton permet de sélectionner un dossier entier au lieu d'un seul fichier. Tous les fichiers audio du dossier sélectionné (y compris les sous-dossiers) sont importés d'un coup.

Un **préfixe** vous sera demandé. Chaque fichier importé sera nommé `PREFIXE-nomoriginal` dans votre projet. Cela permet d'organiser et d'identifier facilement les fichiers par source ou catégorie.

Faites à nouveau un clic droit sur le bouton Import pour revenir en mode fichier unique (**IMPORT FILE**).

### Auto-Assign (importation en masse)

Pour remplir rapidement vos pads :

1. Cliquez sur "Switch to crossfade mode"
2. Cliquez sur le bouton **Auto-Assign**
3. Choisissez l'un des deux modes d'importation :
  - **New Import** : efface tous les pads existants et repart de zéro
  - **Fill empty pads** : conserve vos pads existants et ne remplit que les pads vides (les fichiers déjà assignés à un pad ne sont pas réimportés)
4. Sélectionnez un dossier contenant vos fichiers audio (les sous-dossiers sont inclus)
5. Les fichiers sont automatiquement copiés, assignés aux pads et nommés

Si le dossier contient plus de fichiers que de pads disponibles, les fichiers sont choisis aléatoirement. Chaque Auto-Assign produit ainsi une playlist différente, idéal pour renouveler la musique d'ambiance.

Utile pour préparer rapidement un spectacle avec de nombreuses cues sonores, ou pour compléter un projet existant sans perdre vos pads déjà configurés.

---

## Pads

BlackBox Cue vous offre **300 pads** organisés sur **25 pages** de 12 pads chacune.

Chaque pad peut contenir un fichier audio et possède ses propres réglages de lecture. Alternativement, un pad peut être configuré en **mode Blank** pour jouer du silence pendant une durée configurable: utile pour insérer des pauses calibrées entre les pistes ou pour déclencher des cues de contrôle sans aucun son.

### Jouer un pad

Cliquez simplement sur un pad pour le lancer. Le pad s'allume en vert pendant la lecture.

### Naviguer entre les pages

- Utilisez les boutons **Page Up** et **Page Down** pour changer de page
- Le numéro de la page courante est affiché en haut de l'écran

---

## Mode édition

Pour configurer un pad, passez en **Mode édition** en cliquant sur le bouton **Edit**. Le bouton Edit clignote tant que le mode édition est actif, comme rappel visuel.

En mode édition, cliquer sur un pad le sélectionne pour l'édition (il s'allume en jaune). Vous pouvez alors :

- **Assigner un fichier audio** avec le bouton Browse
- **Définir un nom** (le texte affiché sur le pad, 14 caractères maximum)
- **Choisir un comportement de fin** (ce qui se passe quand la piste se termine)
- **Choisir un comportement de début** (où la lecture commence)
- **Préécouter** les premières secondes du morceau
- **Configurer l'égaliseur** du pad (activer/désactiver, régler les bandes)
- **Appliquer un effet audio** (réverbération, delay, flanger, lo-fi, robot, distorsion, vocal remover)
- **Régler la vitesse de lecture** (50% à 120%, sans modifier la hauteur du son)
- **Passer en mode Blank** pour utiliser le pad comme silence minuté au lieu d'un fichier audio
- **Sauvegarder**

### Pads Blank (mode silence)

Au lieu de jouer un fichier audio, un pad peut être configuré en **mode Blank** pour jouer du silence pendant une durée configurable (1 à 200 secondes). C'est utile pour :

- **Pauses calibrées entre les pistes** : insérer un intervalle silencieux entre deux cues dans une séquence en mode Continue
- **Pads de contrôle uniquement** : utiliser un pad exclusivement pour envoyer des cues MIDI, OSC ou AUDIO à des moments précis, sans qu'aucun son ne soit diffusé

Pour créer un pad Blank :

1. En mode édition, **double-cliquez sur le libellé FILE** (à côté du champ nom de fichier) pour basculer entre le mode FILE et le mode BLANK
2. Utilisez les boutons **-/+** pour régler la durée du silence. Maintenez le bouton enfoncé pour un réglage plus rapide (incréments de 10 secondes)
3. Ajoutez des cues de contrôle dans l'onglet CTRL si nécessaire
4. Cliquez sur **Save**

**Comportement des pads Blank :**

- Le pad joue toujours en mode **Continue**, sans boucle, sans Auto-Trim et sans offset
- L'**égaliseur**, les **effets audio**, le **Pre-Wait**, le **Post-Wait** et la **Vitesse** sont désactivés
- Pendant la lecture, l'afficheur indique « BLANK *n* SECONDS » au lieu du nom de fichier
- **Le crossfade est ignoré** : lorsqu'un pad Blank est en lecture, il joue toujours jusqu'à la fin avant que le pad suivant ne démarre: il n'y a pas de transition crossfade
- Les **cues de contrôle** fonctionnent normalement pendant le silence, synchronisées au temps écoulé du pad
- Le bouton **Clear** remet le pad en mode normal (non-blank)

Pour repasser un pad Blank en mode FILE, double-cliquez à nouveau sur le libellé BLANK. Si un fichier était précédemment assigné, les données du pad (BPM, Auto-Trim, points de fade) sont recalculées à partir du fichier. Si le fichier n'existe plus, le pad est réinitialisé (à l'exception du titre).

### Comportement de fin

- **One-Shot** : la piste est jouée une fois puis s'arrête
- **Loop** : la piste se répète indéfiniment (idéal pour les ambiances sonores ou les boucles musicales)
- **Continue** : quand la piste se termine, le pad suivant se lance automatiquement (idéal pour les conduites séquentielles). En mode crossfade, lorsque le dernier pad assigné se termine, la lecture reprend automatiquement au premier pad assigné. En mode one-shot sur le dernier pad assigné, la lecture se termine par un fondu de sortie progressif

### Comportement de début

- **Start from zero** : la lecture commence au tout début du fichier
- **Auto-Trim** : la lecture saute les silences au début et à la fin du fichier (détectés automatiquement). Remarque : l'Auto-Trim ne fonctionne que si le silence ne dépasse pas 10 secondes. Au-delà de 10 secondes, le silence est considéré comme intentionnel et fait partie intégrante du morceau, il sera donc joué normalement
- **Custom start and end points** : définissez un point de début et un point de fin dans le morceau pour ne jouer qu'une portion précise de la piste: par exemple, uniquement le refrain ou un passage particulier. Utilisez les boutons +/- pour ajuster chaque point. Un écart minimum de 1 seconde est maintenu entre le début et la fin

### Pre-Wait et Post-Wait

Chaque pad peut avoir un **pre-wait** (silence avant la lecture) et un **post-wait** (silence après la lecture), réglables de 0 à 600 secondes.

- **Pre-Wait** : lorsque vous déclenchez un pad, le logiciel attend la durée configurée avant de lancer la lecture. L'afficheur montre un décompte pendant l'attente. Utile pour insérer une pause avant un effet sonore, ou laisser le temps aux artistes de se mettre en place.
- **Post-Wait** : une fois la piste terminée, le logiciel attend avant de passer à l'action suivante (enchaîner le pad suivant ou s'arrêter). L'afficheur montre un décompte pendant l'attente. Utile pour insérer un silence entre deux cues consécutifs.

Le pre-wait et le post-wait ne s'appliquent que lorsque le crossfade est désactivé. En mode crossfade, les pistes enchaînent directement, les temps d'attente ne sont donc pas utilisés.

Utilisez les boutons **+/-** pour ajuster chaque valeur. Maintenez le bouton pour un réglage plus rapide.

### Affichage de la forme d'onde

En mode édition, la forme d'onde du fichier audio est affichée. Cliquez sur la forme d'onde pour basculer entre la vue du **début** et de la **fin** de la piste.

Une ligne jaune indique le point de début Auto-Trim. Une ligne orange indique le point de fin Auto-Trim. Une ligne cyan indique votre offset de début personnalisé. Une ligne rouge pointillée indique la position de fade-out détectée (utilisée par le crossfade AUTO).

L'éditeur affiche également les informations d'analyse du morceau en cours : BPM (tempo) détecté, position du fade-out ou point de baisse d'énergie. Ces données sont utilisées par le crossfade AUTO pour trouver le meilleur moment de transition.

### Égaliseur paramétrique (par pad)

Chaque pad peut disposer de son propre **égaliseur paramétrique 4 bandes**, similaire à ceux des consoles de mixage professionnelles. Cet égaliseur agit directement sur la source audio, **avant** le fader de volume et **avant** l'égaliseur général. Considérez-le comme un outil de préparation et de correction de chaque piste individuellement : supprimer un grondement indésirable, adoucir des fréquences agressives, ou ajouter de la chaleur: indépendamment du volume final de sortie. C'est exactement ce que fait un ingénieur du son lorsqu'il égalise chaque tranche de sa console de mixage avant de toucher au master.

Activez l'égaliseur avec la case **Enable Equalizer**, puis sélectionnez une bande (LOW, LOW MID, HIGH MID, HIGH) et ajustez ses paramètres :

- **Mode** : choisissez le type de filtre pour chaque bande. Les modes disponibles dépendent de la bande :
 - **Low Cut** : supprime toutes les fréquences en dessous de la fréquence de coupure. Utile pour nettoyer les basses fréquences parasites ou les excès de graves dans un enregistrement
 - **Low Shelf** : amplifie ou atténue toutes les fréquences en dessous de la fréquence définie. Permet d'ajouter de la chaleur ou de réduire l'effet « boueux »
 - **High Cut** : supprime toutes les fréquences au-dessus de la fréquence de coupure. Utile pour adoucir les aigus agressifs ou réduire le souffle
 - **High Shelf** : amplifie ou atténue toutes les fréquences au-dessus de la fréquence définie. Permet d'ajouter de la brillance ou de réduire les sifflantes
 - **PEQ** (Parametric EQ) : amplifie ou atténue une plage de fréquences précise, avec le paramètre Q qui contrôle la largeur de la zone affectée. Le mode le plus précis pour des corrections chirurgicales
 - **VEQ** (Vintage EQ) : similaire au PEQ, mais avec une réponse plus large et plus musicale. Se comporte comme les égaliseurs analogiques classiques: mieux adapté aux corrections tonales globales
 - **Off** : la bande est désactivée

  LOW propose Off, Low Cut, Low Shelf, PEQ et VEQ. HIGH propose Off, High Cut, High Shelf, PEQ et VEQ. Les bandes médium proposent Off, PEQ et VEQ
- **Fréquence** : réglez la fréquence centrale ou de coupure de la bande
- **Gain** : amplifiez ou atténuez la plage de fréquences sélectionnée (de -15 à +15 dB)
- **Q** : ajustez la largeur de bande du filtre. Une valeur de Q basse donne une courbe large et douce qui affecte de nombreuses fréquences voisines. Une valeur de Q élevée donne une courbe étroite et précise qui cible une fréquence spécifique

Utilisez les boutons **+/-** pour ajuster chaque paramètre. Maintenez le bouton pour un réglage plus rapide.

Un **graphique de réponse fréquentielle** montre l'effet combiné des quatre bandes en temps réel. Pendant la préécoute, un **spectrogramme en temps réel** défile sur le graphique, montrant le contenu fréquentiel réel de l'audio. Cela vous permet de voir l'effet de vos réglages et de comparer avec/sans égalisation en cochant/décochant la case.

Les réglages de l'égaliseur sont sauvegardés par pad et appliqués pendant la lecture, y compris pendant les transitions crossfade où chaque piste conserve ses propres réglages.

### Égaliseur général (master)

En plus de l'égaliseur par pad, BlackBox Cue propose un **égaliseur paramétrique 4 bandes général** qui s'applique à l'ensemble de la sortie audio. Cliquez sur le bouton **EQ** dans l'interface principale pour ouvrir le panneau de l'égaliseur général.

L'égaliseur général possède les mêmes commandes que l'égaliseur par pad (mêmes bandes, mêmes modes de filtre), mais remplit un rôle très différent. Alors que l'égaliseur par pad corrige chaque source audio individuellement, l'égaliseur général façonne le **son final** qui arrive aux enceintes. Il s'applique **après** l'égaliseur du pad et le fader de volume dans la chaîne audio, et affecte tous les pads et SFX simultanément.

Utilisez l'égaliseur général pour vous adapter à votre environnement de diffusion :
- **Acoustique de la salle** : atténuer les basses envahissantes dans un espace réverbérant, ou renforcer les graves en extérieur
- **Compensation du système de sonorisation** : corriger des enceintes trop brillantes, trop ternes, ou ayant une signature fréquentielle particulière
- **Ajustement en fonction du volume** : à faible volume d'écoute, l'oreille humaine perçoit moins les graves et les aigus (effet Fletcher-Munson). L'égaliseur général permet de compenser en rehaussant légèrement les basses et les aigus lorsque le volume est bas

Un **spectrogramme en temps réel** sur le panneau de l'égaliseur général montre le contenu fréquentiel de la sortie audio principale, incluant tous les pads et SFX en cours de lecture. Lorsque l'égaliseur général est activé, la courbe de l'égaliseur est affichée par-dessus le spectrogramme.

Les réglages de l'égaliseur général sont sauvegardés avec votre projet.

### Effets audio

Chaque pad peut bénéficier d'un **effet audio** appliqué par-dessus son égaliseur. Activez l'effet avec la case **Enable FX**, puis choisissez un mode et un preset :

- **Reverb** : ajoute une sensation d'espace au son. Presets : Room, Hall, Cathedral, Plate
- **Delay** : crée des échos et des répétitions. Presets : Slapback, Echo, Long Delay
- **Flanger** : produit un effet de balayage caractéristique. Presets : Subtle, Medium, Deep
- **Lo-Fi** : dégrade la qualité audio pour un effet vintage ou stylisé. Presets : Radio, Telephone, Vinyl, 8-Bit
- **Robot** : module le son pour un effet de voix robotique. Presets : Low, Mid, High
- **Distorsion** : ajoute de la saturation. Presets : Light, Medium, Heavy
- **Vocal Remover** : atténue le contenu centré (généralement les voix) d'une piste stéréo. Presets : Remove (suppression complète), Bass Keep (préserve les basses)

Utilisez le contrôle **Level** (0-100%) pour doser la quantité d'effet. L'effet est audible immédiatement pendant la préécoute, ce qui permet d'ajuster vos réglages avant la diffusion.

Les réglages d'effet sont sauvegardés par pad et appliqués pendant la lecture, y compris pendant les transitions crossfade.

### Contrôle de vitesse

Chaque pad dispose d'un réglage de **Vitesse** qui permet de modifier le tempo de lecture de **50% à 120%** sans altérer la hauteur du son. La technologie utilisée (time-stretching) préserve la hauteur originale de chaque instrument et de chaque voix : ralentir un morceau donne l'impression que les musiciens jouent plus lentement, et non l'effet d'un vinyle qu'on ralentit. La musique reste naturelle et musicale quelle que soit la vitesse: seul le tempo change.

La vitesse fait partie des réglages FX : elle ne s'applique que lorsque la case **Enable FX** est cochée. Utilisez les boutons **+/-** pour ajuster la valeur de vitesse.

C'est particulièrement utile pour les **écoles de danse et les chorégraphes** : ralentissez un morceau pour apprendre ou répéter une chorégraphie à un rythme confortable, puis remettez la vitesse à 100% pour la représentation. Le même pad, la même piste, deux tempos différents: pas besoin de préparer des fichiers audio séparés.

La vitesse peut être modifiée en temps réel pendant la préécoute, pour entendre immédiatement le résultat. Les réglages de vitesse sont sauvegardés avec le pad.

**Interaction avec les autres fonctions :**

- **Temps écoulé et temps restant** : l'afficheur indique toujours le **temps source** (position dans la piste originale), et non le temps réel écoulé. Une piste jouée à 50% affichera 02:00 de temps écoulé après 4 minutes de temps réel, car seulement 2 minutes de la piste originale ont été lues. Cela signifie qu'un moment musical précis correspond toujours au même temps affiché, quelle que soit la vitesse de lecture: ce qui est essentiel pour les écoles de danse et les chorégraphes qui utilisent des repères temporels comme points de référence pendant les répétitions.
- **Cues de contrôle** : les positions TIME de vos événements de contrôle se réfèrent toujours à la timeline de la piste originale, quelle que soit la vitesse. Une cue placée à 01:30 se déclenchera toujours à 1 minute 30 de la piste originale, même si la lecture est plus lente ou plus rapide.
- **Crossfade AUTO** : en mode AUTO, le crossfade utilise le BPM effectif (le BPM détecté ajusté par le facteur de vitesse) pour calculer les transitions. Le BPM affiché dans l'éditeur correspond toujours au BPM détecté de la piste originale.

---

## Contrôles de lecture

### Stop

Cliquez sur le bouton **Stop** pour arrêter toute lecture en cours, y compris les SFX.

- Si un fade-out est configuré, la première pression lance le fade-out
- Appuyez à nouveau pendant le fade pour arrêter immédiatement

Lorsque vous stoppez une piste **one-shot** (hors mode crossfade), le pad suivant clignote en violet pour indiquer la prochaine cue à jouer - exactement comme lorsque la piste se termine d'elle-même.

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

#### Crossfade AUTO

En mode Continue, vous pouvez régler la durée du crossfade sur **AUTO**. BlackBox Cue analyse alors chaque morceau lors de l'importation et détermine automatiquement le meilleur moment et la meilleure durée pour le crossfade.

Vous n'avez pas besoin de régler manuellement la durée du crossfade - le logiciel s'en charge pour vous, en produisant des transitions naturelles et musicalement cohérentes entre des morceaux de styles et de tempos différents.

---

## Pads SFX

En plus des 300 pads principaux, BlackBox Cue propose **2 pads SFX dédiés** (SFX 1 et SFX 2) pour les effets sonores.

Les pads SFX se jouent **indépendamment** de la lecture principale : vous pouvez déclencher un ou deux SFX pendant qu'un pad principal joue, sans l'interrompre. Les deux pads SFX peuvent aussi jouer simultanément.

Les pads SFX sont toujours en mode **one-shot** (pas de boucle, pas de continue). Ils disposent de leur propre **curseur de volume** (0-130%), indépendant du fader principal. Cela permet de régler un niveau fixe pour vos effets sonores, quel que soit le volume de sortie principal. Les valeurs au-dessus de 100% permettent d'amplifier les effets sonores les plus discrets.

Pour configurer un pad SFX, passez en mode édition et cliquez sur le bouton SFX 1 ou SFX 2. Vous pouvez assigner un fichier audio, choisir un comportement de début et régler le niveau de volume.

---

## Volume

Utilisez le **fader de volume** vertical sur le côté droit de l'écran pour ajuster le volume de sortie. Glissez vers le haut pour augmenter, vers le bas pour diminuer. Vous pouvez aussi utiliser la **molette de la souris** sur le fader pour un réglage rapide.

### Volume de préécoute

Double-cliquez sur le libellé **VOL** au-dessus du fader pour passer en mode **LSTN**. Le fader glisse en douceur vers la position du volume de préécoute. Vous pouvez alors régler le volume de préécoute indépendamment de la sortie principale. Double-cliquez à nouveau pour passer en mode **CTRL**, puis à nouveau pour revenir en **VOL**. Les trois volumes sont toujours indépendants : modifier l'un ne change jamais les autres.

### Volume CTRL

En mode **CTRL** (libellé affiché en bleu), le fader contrôle le volume des **cues audio** (BEEP et SPEAK). Cela vous permet d'ajuster le niveau des rappels de régie et des annonces vocales indépendamment de la lecture principale et de la préécoute. Les cues SPEAK routés vers MAIN utilisent également le volume CTRL, ce qui permet de doser le niveau de la voix-off par rapport à la musique.

### Sélection de la sortie audio

Double-cliquez sur le libellé **MASTER OUT** au-dessus du fader de volume pour ouvrir les réglages de sortie audio. Cette fenêtre permet de configurer trois sorties audio indépendantes :

- **MAIN OUTPUT** : un ou plusieurs périphériques pour la lecture des pads et des SFX
- **PREVIEW / PRE-LISTEN** : un seul périphérique pour la préécoute en mode édition
- **AUDIO CONTROLS** : un ou plusieurs périphériques pour les cues BEEP et SPEAK (rappels de régie, voix-off). Si non configuré, les BEEP ne seront pas joués et les SPEAK routés vers CTRL seront silencieux

### Mono / Stéréo

Double-cliquez sur le libellé **STEREO** pour passer la sortie en **MONO**. En mode mono, les deux canaux sont mixés ensemble, ce qui est utile quand la sonorisation est mono ou quand les enceintes sont très éloignées et que la séparation stéréo serait gênante. Double-cliquez à nouveau pour revenir en stéréo.

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
| F1 - F12 | Jouer le pad 1-12 de la page courante |
| 1 | Jouer SFX 1 |
| 2 | Jouer SFX 2 |
| Espace | Arrêter la lecture |
| Page Up | Page précédente |
| Page Down | Page suivante |

Ces raccourcis sont désactivés lors de la saisie dans un champ texte ou quand une boîte de dialogue est ouverte.

---

## MIDI

BlackBox Cue prend en charge le **MIDI en entrée** (piloter le logiciel depuis un contrôleur MIDI) et les **cues de contrôle** (envoyer des messages MIDI, OSC ou audio vers des équipements externes ou vers vous-même pendant la lecture).

### Activer le MIDI

1. Cochez la case **MIDI** dans l'interface principale
2. Une fenêtre apparaît avec la liste des interfaces MIDI disponibles, en deux sections :
  - **MIDI Input** : choisissez un contrôleur pour piloter BlackBox Cue (clavier, contrôleur à pads, etc.). Sélectionnez un **canal MIDI** (Omni pour écouter tous les canaux, ou un canal spécifique de 1 à 16)
  - **MIDI Output** : choisissez un périphérique vers lequel envoyer les événements MIDI (console lumière, interface DMX, etc.)
3. Cliquez sur **SELECT** pour activer le MIDI

Vous pouvez sélectionner uniquement une entrée, uniquement une sortie, ou les deux en même temps. Décochez la case **MIDI** pour désactiver tout le MIDI.

Un petit indicateur clignote à côté de la case à chaque réception ou envoi d'un message MIDI.

### Activer l'OSC

1. Cochez la case **OSC** dans l'interface principale
2. Une fenêtre apparaît pour configurer la destination OSC :
  - **Adresse IP** : l'IP de l'équipement vers lequel envoyer les messages OSC
  - **Port** : le numéro de port UDP
3. Cliquez sur **OK** pour activer l'OSC

### MIDI en entrée. Piloter BlackBox Cue

| Message MIDI | Action |
|---|---|
| Note On 60 à 71 | Jouer le pad 1 à 12 de la page courante |
| Note On 72 à 96 | Sélectionner la page 1 à 25 |
| Note On inférieure à 60 | Arrêter toute lecture |
| Program Change 1 à 25 | Sélectionner la page 1 à 25 |

La sélection de page (par note ou Program Change) met également à jour la page courante pour les déclenchements de pads suivants.

#### Exemple de configuration

Avec un clavier MIDI standard :
- Utilisez les touches **Do4 à Si4** (notes 60-71) pour déclencher les pads 1-12
- Utilisez les touches **Do5 à Do7** (notes 72-96) pour changer de page
- Utilisez n'importe quelle touche **en dessous de Do4** pour arrêter la lecture
- Envoyez un **Program Change** pour accéder directement à une page

### Cues de contrôle. Envoyer des commandes pendant la lecture

Chaque pad (y compris les pads SFX) peut contenir une liste d'**événements de contrôle** qui sont déclenchés à des moments précis pendant la lecture. Cette fonction est conçue pour piloter des consoles lumière, des interfaces DMX, des équipements scéniques, ou même vous envoyer des rappels audio.

#### Comment ça marche

Chaque événement est défini par :

- **TIME** : le moment pendant la lecture (par rapport au début de la piste) où l'événement doit être déclenché, au format HH:MM:SS
- **CTRL** : le type de contrôle. **MIDI**, **OSC**, **AUDIO**, **SET** ou **PAD**

Les champs suivants dépendent du type CTRL :

**Cues MIDI** (nécessite MIDI Output activé) :
- **TYPE** : **NOTE**, **CC** (Control Change) ou **PROG** (Program Change)
- **CH** : canal MIDI (1 à 16)
- **DATA** : numéro de note, numéro de CC ou numéro de programme (0-127)
- **VAL** : vélocité (pour NOTE), valeur du CC (pour CC) ou non utilisé (pour PROG)

**Cues OSC** (nécessite OSC activé) :
- **TYPE** : type de valeur. **STRING**, **INTEGER** ou **FLOAT**
- **DATA** : l'adresse OSC (ex. `/cue/go`)
- **VAL** : la valeur à envoyer

**Cues AUDIO** (aucun équipement externe requis) :
- **TYPE** : **BEEP** (un signal sonore type carillon) ou **SPEAK** (synthèse vocale)
- **CH** : routage de sortie. **CTRL** (sortie audio controls, par défaut) ou **MAIN** (sortie principale, uniquement pour SPEAK). Les BEEP sortent toujours sur CTRL
- **DATA** : langue pour SPEAK (anglais, français, allemand, espagnol, portugais: détectée automatiquement à partir des modèles vocaux installés). Non utilisé pour BEEP
- **VAL** : le texte à prononcer (pour SPEAK, non utilisé pour BEEP)

Le volume de tous les cues AUDIO (BEEP et SPEAK) est contrôlé par le **fader CTRL**, indépendamment du volume de lecture principal. Les cues SPEAK routés vers MAIN utilisent aussi le volume CTRL, ce qui permet de doser le niveau de la voix-off par rapport à la musique.

#### Cues d'automation (Avancé)

> **Note :** Les cues SET et PAD sont une fonctionnalité avancée destinée aux utilisateurs qui souhaitent une automation fine de leurs spectacles. Il n'est absolument pas nécessaire de les connaître pour utiliser BlackBox Cue efficacement: la grande majorité des utilisateurs n'en aura jamais besoin. Si vous débutez, vous pouvez passer cette section sans hésiter.

En plus de MIDI, OSC et AUDIO, BlackBox Cue propose deux types de contrôle d'automation qui permettent de modifier les réglages du logiciel pendant la lecture: transformant chaque pad en un petit script d'automation.

**Cues SET** (modifier un réglage du logiciel à un instant précis) :
- **TYPE** = **MODE** : basculer entre le mode fade et le mode crossfade. **DATA** : **FADE** ou **CROSSFADE**
- **TYPE** = **NORM** : activer ou désactiver la normalisation du volume. **DATA** : **ON** ou **OFF**
- **TYPE** = **FADEIN** : définir la durée du fade-in (uniquement en mode fade). **VAL** : durée en secondes (0-10)
- **TYPE** = **FADEOUT** : définir la durée du fade-out (uniquement en mode fade). **VAL** : durée en secondes (0-10)
- **TYPE** = **CROSSFADE** : définir la durée du crossfade (uniquement en mode crossfade). **DATA** : **MANUAL** ou **AUTO**. Si MANUAL, **VAL** est la durée en secondes (0-10). Si AUTO, le logiciel détermine automatiquement le meilleur point de transition
- **TYPE** = **VOL** : définir un niveau de volume. **CH** : quel fader. **MAIN**, **LSTN** (préécoute) ou **CTRL** (cues audio). **VAL** : niveau de volume (0-100). Le curseur du fader se déplace à l'écran s'il est actuellement affiché

**Important :** FADEIN et FADEOUT n'agissent que sur les réglages du mode fade. CROSSFADE n'agit que sur le réglage du mode crossfade. Pour changer de mode, utilisez une cue MODE **avant** la cue FADEIN/FADEOUT ou CROSSFADE. Par exemple, pour passer en mode crossfade et définir un crossfade de 5 secondes, placez d'abord une cue `SET / MODE / CROSSFADE`, puis une cue `SET / CROSSFADE / MANUAL / 5` au même instant ou plus tard.

**Cues PAD** (contrôler la lecture à un instant précis) :
- **TYPE** = **STOP** : arrêter toute lecture (identique à un appui sur le bouton Stop)
- **TYPE** = **PAUSE** : mettre en pause ou reprendre la lecture (identique à un appui sur le bouton Pause)
- **TYPE** = **PLAY** : lancer la lecture d'un pad spécifique. **DATA** : numéro de page (1-25). **VAL** : numéro du pad sur la page (1-12). Un pad ne peut pas se cibler lui-même (cela provoquerait une boucle infinie)
- **TYPE** = **PLAYSFX** : déclencher un pad SFX. **DATA** : **SFX1** ou **SFX2**

Ces cues permettent une vraie automation : vous pouvez construire un spectacle où les changements de volume, les transitions crossfade et les enchaînements de pads sont tous pré-programmés et se déclenchent automatiquement au bon moment: sans aucune intervention manuelle pendant la représentation.

#### Cas d'usage des cues AUDIO

- **Rappels de cues scéniques** : envoyez un bip ou un message vocal sur la sortie CTRL pour vous rappeler de déclencher un changement lumière, un mouvement de rideau ou toute action manuelle pendant le spectacle
- **Remplacer ou compléter une conduite papier** : programmez des instructions vocales comme « lumière fondu bleu » ou « rideau » sur la sortie CTRL pour ne plus avoir besoin de lire un script papier pendant le spectacle
- **Voix-off pour le public** : routez un cue SPEAK vers MAIN pour faire une annonce directement au public (par ex. « Le spectacle commence dans 5 minutes »), avec le niveau de la voix-off contrôlé indépendamment par le fader CTRL
- **Tops audio pour des équipements sans MIDI ni OSC** : envoyez un bip ou un message vocal dans le casque connecté à la sortie CTRL pour qu'un régisseur lumière (ou tout autre technicien) sache quand déclencher ses cues manuellement, même si sa console n'a ni entrée MIDI ni OSC
- **Coordination d'équipe via intercom** : branchez la sortie CTRL sur un module d'intercommunication pour que l'ensemble des régisseurs (poursuite, régie plateau, régie lumière, etc.) entendent les tops et les actions données par la synthèse vocale. BlackBox Cue se transforme en « chef d'orchestre » qui synchronise toute l'équipe en leur indiquant quoi faire et quand, en rythme avec la musique

#### Ajouter des événements de contrôle à un pad

1. Passez en **mode édition** et sélectionnez un pad (ou un pad SFX)
2. Le tableau des cues s'affiche sous les réglages du pad
3. Cliquez sur **+** pour ajouter une nouvelle ligne d'événement
4. Sélectionnez le type CTRL, puis remplissez les champs correspondants
5. Cliquez sur **Save** pour enregistrer les événements avec le pad

Les événements sont automatiquement triés par ordre chronologique. Vous pouvez ajouter autant d'événements que nécessaire par pad.

#### Comportement pendant la lecture

- Les événements sont envoyés au bon moment pendant la lecture, synchronisés avec le temps écoulé de la piste (le Pre-Wait et le Post-Wait n'affectent pas le timing)
- Les événements **MIDI NOTE** envoient un Note On immédiatement, suivi d'un Note Off automatique 500 ms plus tard
- Les événements **MIDI CC**, **PROG** et **OSC** sont envoyés immédiatement
- Les événements **AUDIO SPEAK** sont pré-générés en arrière-plan quelques secondes avant leur déclenchement pour éviter toute latence pendant la lecture
- Pendant un **crossfade**, les pistes entrante et sortante envoient leurs cues indépendamment
- Les cues de contrôle fonctionnent indépendamment du MIDI Input: vous n'avez pas besoin d'un contrôleur MIDI pour les utiliser. Les cues MIDI nécessitent MIDI Output activé, les cues OSC nécessitent OSC activé, et les cues AUDIO fonctionnent sans aucun équipement externe
- Si vous naviguez à une autre position pendant la lecture (en cliquant sur la barre de progression), les cues passées sont ignorées et seules les cues à venir seront envoyées

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
- **Conduites séquentielles sans timeline** : Pas besoin de timeline ni de séquenceur pour piloter un spectacle scripté. Il suffit de mettre plusieurs pads consécutifs en mode **Continue**, et le dernier pad de chaque séquence en **One-Shot**. Quand vous lancez le premier pad, la séquence se déroule automatiquement et s'arrête à la fin. Pour la scène suivante, lancez le pad suivant (ou passez à la page suivante) et démarrez une nouvelle séquence. Cette approche est bien plus facile à mettre en place que la programmation de cues sur une timeline: n'importe qui peut le faire, même sans expérience en régie. Et cela reste totalement flexible : vous pouvez sauter une cue, en rejouer une, ou sauter à n'importe quel pad à tout moment pendant le spectacle.

---

## Démarrage rapide : playlist d'ambiance

Mettre en place une playlist musicale pour une salle d'attente, un restaurant ou une exposition prend moins d'une minute :

1. Créez un nouveau projet
2. Passez en mode crossfade
3. Cliquez sur le bouton **Auto-Assign**, choisissez **New Import**, puis sélectionnez un répertoire contenant vos fichiers musicaux. Si le répertoire contient plus de fichiers que de pads disponibles, les fichiers sont choisis aléatoirement. La lecture bouclera automatiquement une fois le dernier morceau terminé
4. Cliquez sur le bouton **Norm** sous le fader de volume pour activer la normalisation
5. Réglez le volume de sortie au niveau souhaité
6. Réglez le crossfade à environ 5 secondes pour des transitions en douceur, ou choisissez **AUTO** pour laisser BlackBox Cue trouver le meilleur moment de transition pour chaque morceau
7. Lancez la lecture du premier pad

C'est tout: votre playlist tourne toute seule avec des enchaînements fluides entre les pistes.

**Astuce :** Si vous importez un jingle (fonction Import) en mode Continue, vous pouvez ensuite assigner ce même jingle à plusieurs pads sur des pages différentes. Cela permet d'intégrer un jingle à différents endroits de la playlist. On peut faire de même avec des spots publicitaires.

---

## Installation et avertissements de securite

BlackBox Cue est un freeware. Les executables ne sont **pas signes numeriquement** (les certificats de signature de code sont couteux et ne se justifient pas pour une application gratuite). Pour cette raison, votre systeme d'exploitation peut afficher un avertissement de securite lors du premier lancement. C'est tout a fait normal: voici comment proceder selon votre plateforme.

### Windows

Lors du premier lancement de BlackBox Cue, Windows SmartScreen peut afficher une fenetre bleue indiquant **"Windows a protege votre ordinateur"**.

1. Cliquez sur **Informations complementaires** (le lien sous le texte d'avertissement)
2. Cliquez sur **Executer quand meme**

Cet avertissement n'apparait qu'une seule fois. Windows retiendra votre choix et ne vous le redemandera plus.

### macOS

macOS Gatekeeper bloque par defaut les applications provenant de developpeurs non identifies. Lorsque vous essayez d'ouvrir BlackBox Cue pour la premiere fois, un message indique que l'application **"ne peut pas etre ouverte car elle provient d'un developpeur non identifie"** (ou **"Apple ne peut pas verifier qu'il ne contient pas de logiciel malveillant"**).

1. Fermez la fenetre d'avertissement
2. Ouvrez les **Reglages Systeme** (menu Apple > Reglages Systeme)
3. Allez dans **Confidentialite et securite**
4. Faites defiler vers le bas: vous verrez un message indiquant que BlackBox Cue a ete bloque. Cliquez sur **Ouvrir quand meme**
5. Entrez votre mot de passe ou utilisez Touch ID pour confirmer
6. Une nouvelle fenetre apparait: cliquez sur **Ouvrir**

Cette autorisation ne doit etre effectuee qu'une seule fois. Apres cela, macOS vous laissera ouvrir BlackBox Cue normalement.

---

## Credits

BlackBox Cue utilise les bibliothèques et ressources suivantes :

**Moteur audio et traitement :**

- [SoLoud](https://solhsa.com/soloud/) - Moteur audio portable
- [FFmpeg](https://www.ffmpeg.org) (LGPL v2.1) - Décodage audio. Compilé en mode LGPL (`--disable-gpl`) et utilisé en bibliothèque dynamique. Options de compilation : `./configure --enable-shared --disable-static --disable-gpl --disable-programs --disable-doc --disable-network --disable-encoders --disable-muxers --disable-devices --disable-filters --enable-demuxers --enable-decoders --enable-protocols=file`
- [SoundTouch](https://www.surina.net/soundtouch/) (LGPL v2.1) - Time-stretching pour le contrôle de vitesse
- [SQLite](https://www.sqlite.org) - Base de données embarquée pour les fichiers projet

**Synthèse vocale :**

- [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) (Apache 2.0) - Moteur TTS utilisant ONNX Runtime

**Modèles de voix (inclus) :**

- Anglais : en_US-kristin-medium (Public Domain) - [Piper TTS](https://github.com/rhasspy/piper)
- Français : fr_FR-siwis-medium (CC BY 4.0) - [SiwisFR / Idiap Research Institute](https://datashare.ed.ac.uk/handle/10283/2353)
- Allemand : de_DE-eva_k-x_low (BSD 3-Clause) - [M-AILABS](https://github.com/i-celeste-aurora/m-ailabs-dataset)
- Espagnol : es_ES-davefx-medium (CC0) - [OHF-Voice](https://github.com/OHF-Voice/voice-datasets)
- Portugais : pt_BR-faber-medium (CC0) - [OHF-Voice](https://github.com/OHF-Voice/voice-datasets)

---

## Licence

Copyright (c) 2025 Cyril LAMY. Tous droits réservés.

Ce logiciel est un **FREEWARE**. Vous pouvez l'utiliser et le distribuer librement à des fins personnelles ou commerciales.

**AVERTISSEMENT :** Ce logiciel est fourni « en l'état », sans garantie d'aucune sorte. L'auteur ne pourra être tenu responsable de tout dommage ou préjudice découlant de l'utilisation de ce logiciel.

---
