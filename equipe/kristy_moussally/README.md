# Kristy Moussally

![](kristy.jpg)

### Semaine 1

- Création du concept du projet (expérience)
- Affinage de la partie technique (plan synoptique et plan d’implantation)
- Estimation du budget de l’équipement

### Semaine 2

- Création des assets visuels des obstacles (déchets)
- Création des assets visuels de l'interface virtuel (des bras mécanique munis d'un aspirateur)
- Création des assets visuels des créatures (poissons, tortue,...)
- Création des assets visuels du paysage (algues, roches, sable, figure de fond)

- Partage de quelques médias visuels bruts pour le prototype (maquette 1)

### Semaine 3

- Faire la réservation d'équipement et du studio pour enregistrer des sons (préparation pour la semaine 4)

- Améliorer les assets visuels pour préparer à l'animation
- Commencer les animations des assets visuels du paysage (mouvement des bras mécaniques, aspiration des objets par l’aspirateur, déchets qui coulent au fond, images de fond dynamiques et créatures marines qui nagent)

- Préparation du prototype de l'interface visuel (Communication entre l'ordinateur vers un moniteur)

- Partage des animations dans Unity (remplacement des placeholders par des éléments esthétiques)

### Semaine 4

- Réservation de l'équipement d'enregistrement et du studio pour la vidéo de bande-annonce (préparation pour la semaine 5)

- Enregistrement des sons pour les déchets, des sons mécaniques pour le sous-marin (bras mécanique + aspirateur et son exécution)
- Traitement et modification des effets sonores des sons enregistrer (créature, mécanique du sous-marin en action, déchets qui coulent au fond ) par Reaper
- Création de l'ambiance sonore par Wavetable VST dans Reaper

- Correction du visuel et aspects sonores dans Unity

### Semaine 5

- Retouchement du visuel et aspects sonores dans Unity

- Installation du câblage du moniteur

- Partage des sons dans Unity (l'interaction des modules Arduino et autres éléments dynamiques du jeu)

- Rédiger une partie du dossier de presse (images, à propos de l'équipe, crédits et contact)

- Filmer et enregistrer l'interaction du projet pour la bande-annonce

### Semaine 6

- Présentation de la maquette 2

- Organisation des câbles de l'arcade

- Installation technique finale du projet

### Semaine 6.5

- Réparer des parties technique de communication de l'ordinateur et l'arcade

- Améliorer le câblage de l'installation

### Semaine 7

- Retouche de l’interface visuelle

- Filmer l'assemblage de l'installation pour la vidéo de la documentation du projet
- Contribuer à la construction de la cardre du moniteur (écran et fenêtre)
- Test de contrôle de la qualité du projet (réparer les erreurs d'animation)
- Optimisation de l'application (diminuer le poids des assets visuels) (projet Unity)

### Semaine 8

- Présentation du projet (prise en charge de l’ouverture et de la fermeture du projet)
- Filmer l'interaction avec l'installation pour la vidéo de la documentation du projet
- Désinstaller le projet (vendredi)
- Retouner l'équipement (vendredi)

## Journal de bord

Cette section, complétée **quotidiennement** pendant l’exécution du projet, documente le travail individuel réellement réalisé chaque jour.

<!--
- Une entrée par jour sur 8 semaines (8 semaines à partir de la semaine 2).
   - Un total d'au moins 40 entrées uniques!
- Chaque jour :
    - Documentstion visuelle et/ou sonore du travail effectué
    - Lien vers les billets GitHub résolus
- Démarche rigoureuse de validation de la qualité
- Démonstration d'autonomie.
- Exécution technique précise et complète.
- Évaluation réfléchie de la contribution individuelle au travail d’équipe.
-->

### Semaine 2

#### Lundi

Dessiner, en vectoriel, le paysage (image de fond) avec plusieurs couches afin de créer un effet de parallaxe.

- Sable
- Algues (statiques)
- Cailloux
- Rocher en arrrière-plan
- Océan (image de fond)

![Visuel de l'environnement (Photoshop) - version prototype](visuel_01.png)
** Le paysage devrait être utilisé comme texture dans un environnement 3D (Maya est requis pour obtenir l’effet nécessaire) **

#### Mardi

Dessiner, en vectoriel, les déchets avec plusieurs versions afin de diversifier les obstacles de l'interacteur (joueur).

- Bouteille en plastique
- Bouteille en verre
- Sac
- Cannette

![Visuel des déchets (Photoshop) - version prototype](visuel_02.png)

#### Mercredi

Communiquer l’arcade (le moniteur) avec une tour (poste d’ordinateur du chariot) à l’aide d’un extendeur vidéo.

Dessiner, en vectoriel, le bras mécanique muni d’un aspirateur avec plusieurs couches pour l’animation.

Redessiner, en vectoriel, les obstacles (déchets) dans Illustrator afin d’ajuster leur taille et d’améliorer leur design.

- Bras mécanique avec aspirateur
- Bouteille en verre
- Bouteille en plastique
- Cannette
- Sac
- Mettre à jour la liste d’équipement nécessaire pour l’arcade

![Visuel de l'aspirateur - version prototype](visuel_03.png)

![Visuel des déchets (Illustrator) - version 2D](visuel_04.png)

![Connection du moniteur d'arcade et la tour](Media_01.jpg)

#### Jeudi

Contextualiser l’esthétique sonore du projet (paragraphe du concept sonore).

Dessiner, en vectoriel, les créatures marines et les préparer pour l’animation.

Modéliser des cylindres dans Maya, avec la texture du paysage, afin de créer un effet de parallaxe dans Unity (modèle 3D en 2D).

- Poissons
- Tortue de mer

![Visuel des poissons (Illustrator) - version prototype](visuel_05.png)
![Visuel de tortue de mer (Illustrator) - version prototype](visuel_06.png)
![Visuel du paysage dans un environnement 3D - version prototype](visuel_07.png)
![Visuel du paysage dans Unity - test](visuel_08.png)

#### Vendredi

Animer l’aspirateur lors de son activation (les bulles sont aspirées à l’intérieur de l’aspirateur).

Animer le bras mécanique, influencé par l’aspirateur lors de son activation (mouvement robotique).

- Aspiration d’un déchet (activation)
- Mouvement du bras mécanique influencé par l'aspiration (activation)

![Animation de l'activation de l'aspirateur](visuel_09.png)
![Animation de l'activation de l'aspirateur dans unity - test](visuel_10.png)

### Semaine 3

#### Lundi

Réserver l’équipement nécessaire (portable) pour l’enregistrement des sons (semaine 4).

Animer l’écoulement des déchets dans l’océan.

** Cette animation ne sera pas utilisée en raison de la gravité dans Unity **

Animer la dégradation des déchets lorsqu’ils atteignent le fond de l’océan (des bulles cachent l’objet en remontant).

- Bouteille en verre
- Bouteille en plastique
- Cannette
- Sac

![Animation de dégradation du déchet](visuel_12.png)
![Animation spritesheet des déchets de dégradation et de coulement préparer dans Figma](visuel_11.png)
![Animation de dégradation du déchet dans unity - test](visuel_13.png)

#### Mardi

Réserver l’équipement nécessaire (dans le petit studio) pour l’enregistrement des sons (semaine 4).

Redessiner, en vectoriel, le paysage dans Illustrator afin de le préparer pour l’animation (version dynamique).

Animer des créatures qui nagent (en boucle dans l’espace virtuel).

Mouvement fluide influencé par une technique de marionnette pour la tortue.

Mouvement fluide accompagné d’une ondulation pour l’animation des poissons.

Animer l’apparition et la disparition des créatures (influencées par la pollution accumulée durant le jeu).

- Poissons
- Tortue de mer

![Animation de la tortue de mer dans After Effects](visuel_14.png)
![Animation spritesheet des créatures marines préparer dans Figma](visuel_15.png)
![visuel de l'environnement (Illustrator) - préparation version dynamique](visuel_16.png)
![Animation de l'environnement avec mouvement des algues et bulles - version dynamique](visuel_17.png)

#### Mercredi

Débrancher la communication entre l’arcade et l’ordinateur du chariot pour les portes ouvertes.

Préparation du projet (maquette 1) sur l’ordinateur du chariot pour les portes ouvertes.

Nettoyer le câblage de l’ordinateur du chariot pour son déplacement au grand studio.

Animer les algues et les bulles séparément du paysage / environnement afin d’avoir plus de contrôle sur leur interaction avec la pollution.

- Mouvement des algues fluides
- Bulles montent des rochers

Tester le build du projet Unity.

#### Jeudi

Modéliser des cylindres avec la texture du paysage dynamique afin de créer un effet d’immersion dans Unity (module 3D en 2D).

![Animation de l'environnement dans unity - version dynamique](visuel_18.png)
![Animation spritesheet de l'envirennement - plus de contrôle dans unity](visuel_19.png)

Déplacement du projet (ordinateur du chariot) devant le Grand studio pour les portes ouvertes.

Préparer le build du projet Unity (maquette 1) sur l’ordinateur du chariot.

#### Vendredi

Apporter l’équipement audio (portable) pour enregistrer les sons nécessaires à la semaine 4.

Créer l’ambiance de pollution (ambiance sombre sur la caméra pour donner la sensation de progression du déroulement).

Animer un signal pour indiquer aux interacteurs la présence de déchets hors de leur champ de vision,
inspiré par le mouvement des ondes sonores et d’un radar.

![Animation du signal pour la détection des déchets hors de la vision du sous-marin dans After Effects](visuel_20.png)
![Visuel de la pollution sur la fenêtre pour indiquer la progression d'aspiration des déchets - test dans unity](visuel_21.png)

Faire une liste des effets sonores à enregistrer ou à créer :

- Bulles
- Objets submergés (sac, cannette, bouteille)
- Sons de machines (étirement, rotation d’élastique, mouvement des joints)
- Aspiration (activation de l’aspirateur)
- Son du signal (interface de la machine)
- Rotation du volant (mouvement du sous-marin)
- Déchets tombant sur le sable (contact avec le sol)
- Sons des créatures marines (mouvements sous l’eau)
- Déchets en train de se désintégrer (dégradation)
- Ambiance sombre et harmonieuse

### Semaine 4

#### Lundi

Enregistrement des sons dans le petit studio :

- Bulles
- Eau en mouvement
- Déchets (plastique, sac)
- Sons mécaniques pour les bras robotiques
- Aspirateur (activation)

![Enregistrement des sons dans le petit studio](Media_02.jpg)

#### Mardi

Séparer à nouveau les parties du bras mécanique (asset visuel en plusieurs couches) pour l’exporter en PSB (de Photoshop vers Unity).

Faire le rigging (squelette) du bras mécanique pour préparer l’inverse kinematics dans Unity.

Faire le rigging (squelette) de l’aspirateur pour préparer l’inverse kinematics dans Unity.

Refaire l’interaction du bras mécanique dans l’espace (inverse kinematics).

Refaire l’animation des tortues lors de leur disparition, au cas où l’animation d’opacité dans Unity ne serait pas très fluide.

#### Mercredi

Finaliser l’inverse kinematics du bras mécanique avec une cible (viseur) pour le manipuler avec le joystick.

Ajouter l’animation des bulles lors de l’aspiration (activation de l’aspirateur) dans le prefab de l’aspirateur (squelette/rig).

Corriger l’erreur dans l’animation des poissons (petite coupure de l’ondulation vers la fin du loop).

Séparer l’illustration de la pollution sur la fenêtre du sous-marin en différentes phases, afin de montrer la progression de la pollution au fil de l’expérience.

![Manipulation du IK du bras mécanique et l'aspirateur dans unity - test](visuel_22.png)

#### Jeudi

Travailler sur les effets sonores.

Manipuler et couper les sons enregistrés.

Ajouter des effets (écho et sons sous l’eau).

- Mouvement du bras mécanique
- Activation de l'aspirateur
- Déchet aspiré
- Déchet touche le sable (tombe au fond)
- Déchet se dégrade
- Son du signal (inspirer du radar)
- Découpage d'extrait de son pour préparer à l'ambiance

[Extrait sonore d'un objet absorbé par l'aspirateur](dechet_absorbe.mp3)
[Extrait sonore d'un objet qui touche le fond de l'océan](dechet_tombe_sol.mp3)

![Manipulation/modification des effets sonores](visuel_23.png)

#### Vendredi

Clarifier les tâches dans le journal de bord.

Mettre à jour les tâches hebdomadaires pour préparer les évaluations de la semaine 6.

Finaliser les effets sonores.

- Mouvement du bras mécanique (avoir une différence avec la rotation du sou-marin)
- Son du signal (aligner avec l'animation)
- Sous-marin qui tourne (tourner le "volant")
- Son de créature
- Composition de l'ambiance général

[Extrait sonore des créatures marines (une partie de l'ambiance)](creatures.mp3)

[Extrait sonore du signal](signal.mp3)

![Calibration du son du signal avec son animation](visuel_24.png)

Composer l’ambiance générale dans Reaper et Wavetable (couper et ajouter des extraits sonores).

Modéliser deux autres déchets avec la texture 2D finale afin de conserver l’effet 2D dans la scène Unity (module 3D en 2D).

![Modélisation de la bouteille en plastique et de la cannette avec leur texture 2D dans Maya](visuel_25.png)

Réserver l’équipement pour le montage (préparation de la bande-annonce).

### Semaine 5

#### Lundi

Mettre à jour les matériaux nécessaires pour l’arcade (bois, module Arduino).

Retoucher les effets sonores du sous-marin, notamment le mouvement du bras mécanique et la rotation de la caméra.

Finaliser l’ambiance générale (compiler les extraits sonores coupés et ajuster les effets).

Séparer les pistes d’ambiance sombre et d’ambiance harmonieuse.

[Extrait sonore l'ambiance - version ensemble](ambiance.mp3)

![Composition de l'ambiance général](visuel_26.png)

Animer les bulles pour l’animation de dégradation des déchets dans Maya.

Exporter l’animation des bulles (baked) de Maya vers Unity pour préparer l’animation de dégradation des déchets.

![Animation des bulles pour la dégradation des déchets dans Maya](visuel_27.png)
![Animation des bulles pour la dégradation des déchets dans unity](visuel_28.png)

#### Mardi

Programmer le fonctionnement du joystick 3 axes modèle 4D00B-M4.

Communiquer avec le joystick via PureData.

Utiliser Arduino Nano pour disposer de plus de ports analogiques.

Le joystick comprend un bouton, une rotation sur lui-même, ainsi que le contrôle des axes X et Y.

- Fils rouges = 5v (voltage/power)

- Fils bleux foncés et un blanc = analogue (entré analogue des mouvements)

- Fils noirs = GND (Ground)

- Fils bleux claires = GND (Ground) et un numérique (entré numérique du bouton)

![Communication entre le code du joystick et le pureData](visuel_29.png)
![Circuit du joystick - vue de face](joystick.jpg)
![Circuit du joystick - vue de haut](joystick_2.jpg)

#### Mercredi

Réparer les sons de l’aspirateur lors de l’activation (suppression du délai).

Modifier le son de la rotation de la caméra afin d’obtenir un effet constant lors de la manipulation du joystick.

![Modification du son d'aspirateur dans Reaper](visuel_30.png)

Ajouter l’animation des bulles avec les déchets dans Unity.

Programmer le déclenchement de l’animation de dégradation, influencé par un timer (travail encore en cours).

![Ajouter l'animation des bulles dans les prefabs - unity](visuel_31.png)

#### Jeudi

Reprogrammer le déclenchement des animations de dégradation (bulles et déchets).

Optimiser les animations de dégradation des déchets directement dans Unity.
(Réduire la taille du code et modifier le type d’animation en Legacy pour réduire les alertes dans la console.)

Calibrer l’activation des animations des déchets avec le son de dégradation.

![Programmation de l'animation de dégradation - unity](visuel_32.png)

#### Vendredi

Connecter les haut-parleurs de l’arcade à une autre carte audio via un câble Jack.

Contribuer à la construction du panneau de contrôle (installer le joystick et l’Arduino Terminal sur le bois).

Filmer l’interaction avec l’installation pour le montage vidéo (bande-annonce).

![Prépraration du filmage de la bande annonce - Enregistrement de l'interaction avec l'installation](Media_03.jpg)

Créer la bannière pour le projet.
![Bannière de notre projet : Océan Rouge](banniere.png)

(À envoyer la bannière au comité responsable du site web)

Faire la partie image, à propos de l'équie, crédits puis contact du dossier de presse.

### Semaine 6

#### Lundi

Préparer la maquette 3 (ordinateur du chariot et arcade).

Organiser le câblage de l’ordinateur du chariot pour son déplacement devant le Grand studio.

Retirer l’équipement non nécessaire sur le chariot (haut-parleurs externes, clavier, etc.).

![Prépraration de déplacement du projet vers le Grand studio](Media_04.jpg)

![Organiser les câbles en arrière de l'arcade](Media_05.jpg)

Mettre à jour la page d’accueil et la maquette :

- Modifier la partie collective dans la description du projet
- Ajouter le logiciel OBS dans la liste des logiciels utilisés
- Changer le titre du projet de « Océan rouge » à « Océan Rouge »

#### Mardi

Déplacer l’installation devant le Grand studio.

Ajouter des câbles d’extension :

- XLR pour l’audio + carte de balancement stéréo
- USB-B pour la communication entre l’Arduino Terminal et l’ordinateur
- Câble Ethernet plus long entre le récepteur et le transmetteur (extendeurs)

Présenter la maquette 2 (le projet) aux étudiants du cours 570 V11 MO – Œuvres et dispositifs multimédias en exposition.

![Installation du projet devant le Grand studio](Media_06.jpg)

#### Mercredi

Restituer au TTP les anciens haut-parleurs de la maquette 1.

Retirer les câbles XLR non nécessaires.

Dessiner, en vectoriel, le joystick pour animer ses fonctions (partie explicative visuelle).

Animer la manipulation du joystick : bouton, rotation et mouvements des axes X et Y.

![Illustration vectoriel de joystick](visuel_35.png)

![Animation de rotation du joystick](visuel_33.png)

![Spritesheet des animations du joystick](visuel_34.png)

Ajouter le package Post Processing dans Unity pour appliquer l’effet Fisheye sur la caméra.

Implémenter l’effet de distorsion des lentilles dans Unity.

![Effet de distortion de a caméra dans unity - test](visuel_36.png)

#### Jeudi

Modéliser un crabe dans Maya avec une texture unie afin de conserver l’effet 2D.

Créer un squelette (rigging) pour animer les articulations du crabe.

Animer un cycle de marche pour le crabe, puis baker son animation pour l’exporter dans Unity.

![Modélisation du crab dans Maya](visuel_37.png)

![Animation du cycle de marche pour l'exporter dans unity](visuel_41.png)

![Implémenter le crab avec son animation dans unity - test](visuel_39.png)

Dessiner, en vectoriel, une baleine dans Illustrator pour l’animer.

Animer la baleine avec une technique de marionnette dans After Effects.

![Illustration vectoriel de la baleine](visuel_38.png)

![Animation de la baleine](visuel_40.png)

Dessiner, en vectoriel, des plantes marines dans Illustrator afin de varier l’environnement (l’écosystème).

Animer les nouvelles plantes marines avec un effet d’ondes dans After Effects.

![Illustration vectoriel des plantes](visuel_42.png)

![Animation d'une des plantes](visuel_43.png)

![Spritesheet des animations des plantes](visuel_44.png)

![Implémenter les nouvelles plantes marine avec leur animation dans unity - test](visuel_45.png)

#### Vendredi

Ajouter et créer des effets sonores variés afin de diversifier l’environnement :

- Déclenchement de l’aspirateur (variante)
- Déchet absorbé (variante)
- Déchet touchant le sol (variante)
- Déchet se dégradant (variante)
- Baleine
- Effets sonores pour le fonctionnement du joystick à l’accueil (rotation, position et bouton)

Programmer le déclenchement de ces sons variés avec des niveaux de pitch et de volume différents à l’aide d’une fonction aléatoire (Random).

[Extrait sonore d'un objet absorbé par l'aspirateur - autre variant](dechet_absorber_2.mp3)
[Extrait sonore de l'aspirateur - autre variant](aspirateur_2.mp3)
[Extrait sonore d'une baleine](baleine.mp3)

![Manipulation/modification des effets sonores pour créer des sons variantes](visuel_46.png)
![Manipulation/modification des effets sonores pour les fonctions du joystick](visuel_48.png)

![Script du déclenchement des sons par un random sur le clip, pitch et volume - test](visuel_47.png)

### Semaine 6.5

#### Lundi

Acheter un nouveau moniteur pour remplacer l’ancien.

![Le nouveau moniteur qui va remplacer le plus petit écran](Media_07.jpg)

#### Mardi

Connecter le câble d’alimentation à la multiprise et le câble HDMI du moniteur à l’extendeur.

Configurer les paramètres de luminosité de l’écran (brightness).

Établir la communication entre le nouveau moniteur et l’ordinateur du chariot à l’aide de l’extendeur.

Mettre à jour la page technique :

- Ajouter le nouveau moniteur dans la liste de l’équipement et du budget
- Modifier le placement de l’installation vers le fond du Grand studio (plan d’implantation 2D)
- Prévoir un seul joystick et arrondir le cadre du hublot dans le plan d’implantation 2D (supprimer les modules non nécessaires)
- Mettre à jour le plan synoptique (connections de l’ordinateur, du moniteur, de la carte son, etc.)

![Enlever équipement audio pour mettre en place le câble d'alimentation du nouveau moniteur](Media_08.jpg)
![Connection HDMI à l'aide du l'extendeur](Media_09.jpg)
![Communication entre l'ordinateur et le nouveau moniteur](Media_10.jpg)

Remplir les informations du projet pour le comité d’émulation.

Créer l’effet sonore du crabe en marche (son d’ambiance).

[Extrait sonore du crab](crab.mp3)

#### Mercredi

Je n'ai pas travaillé aujourd'hui.

#### Jeudi

Je n'ai pas travaillé aujourd'hui.

#### Vendredi

Ajouter un délai pour le son de la baleine.

Ajouter les liens vers mon portfolio et celui de ma collègue dans le dossier de presse.

### Semaine 7

#### Lundi

Remanipuler le son du crabe afin d’assurer la continuité du loop.

[Extrait sonore modifié du crab](crab_modifier.mp3)

![Manipulation/modification de l'effet sonore du crab](visuel_49.png)

Remplir le tableau indiquant les responsables de l’installation lors de la présentation (dans le dossier d’exposition).

Établir une liste brute des étapes d’ouverture du projet pour la présentation finale.

Modifier certaines tâches hebdomadaires de la semaine 4 à 8 pour qu’elles soient alignées avec le journal de bord.

Tracer le cadre pour ressembler à une fenêtre hublot (à vérifier demain pour le découpage).

![Préparation pour le découpage de la cadre du moniteur](Media_11.jpg)

#### Mardi

Recentrer le design et les mesures du cadre pour préparer le découpage.

Ajouter l’effet Fisheye sur la caméra dans Unity (distorsion de l’objectif).

![Effet de distortion de a caméra dans unity](visuel_50.png)

Remplacer le cadre par un bois plus mince et refaire les mesures pour l’intégrer dans le cabinet d’arcade.

Découper le nouveau cadre pour le moniteur (retirer le cercle et ajuster la hauteur du bois).

Peindre la première couche du cadre en noir pour assurer la cohérence visuelle avec le cabinet d’arcade et le panneau de contrôle.

![Peinture sur la nouvelle cadre après le découpage du bois](Media_12.jpg)

Filmer la progression de la peinture pour la documentation.

Nettoyer l’espace de travail (tables, bois, câbles, cabinet d’arcade, feuilles, etc.).

Créer un design du titre inspiré de notre bannière pour l’apposer sur l’arcade.

![Design à faire en carton pour l'arcade](visuel_51.png)

#### Mercredi

Apporter des modifications à notre page concept afin qu’elle soit alignée avec le projet actuel.

#### Jeudi

Acheter les vis manquantes pour le panneau de contrôle.

Acheter un autre tube de peinture (noir de mars) au cas où il n’y aurait pas assez pour la dernière couche du cadre.

Peindre la dernière couche du cadre.

Dessiner, en vectoriel, le titre afin d’obtenir une bonne qualité visuelle en PDF.

Ajuster les paramètres dans le PDF pour l’imprimer.

![visuel du titre - format lettre](visuel_53.png)
![Préparation à imprimer le titre - dans PDF](visuel_52.png)

Imprimer les titres séparément pour ajuster leur taille en fonction de la longueur de l’arcade.

![Titre imprimé et préparation au découpage des marges](Media_13.jpg)

Placer l’ordinateur (tour) sous le cabinet d’arcade.

![Placer la tour sous l'arcade](Media_16.jpg)

Déplacer l’arcade dans le Grand studio.

![Placer l'arcade à propos du plan des installations](Media_14.jpg)

Préparer les équipements sonores à installer et à ajuster demain.

![Préparer l'équipement sonore du projet](Media_15.jpg)

#### Vendredi

Organiser tous les reçus des achats liés au projet.

Implémenter la carte son et ajuster le volume du projet.

![Connection de la carte de son et les haut-parleurs](Media_17.jpg)

Contribuer à l’assemblage du panneau de contrôle.

Ajouter la fenêtre hublot (cadre) sur le cabinet de l’arcade.

![Assemblage de l'interace de l'arcade (cadre et panel de contrôle)](Media_19.jpg)

Corriger la liste des étapes pour l’ouverture.

Tester les builds de la maquette finale sur l’arcade.

![Faire quelques test du projet](Media_18.jpg)

Enregistrer l’audio pour la vidéo de documentation.

Enregistrer l’introduction ainsi que l’interaction du projet pour la vidéo de documentation.

![Enregistrer l'interaction du jeu dans le grand studio](Media_20.jpg)

![Filmer notre introduction dans le petit studio](Media_22.jpg)

![Enregistrer l'audio dans le petit studio](Media_21.jpg)

### Semaine 8

#### Lundi

Mettre à jour la procédure d’ouverture quotidienne du projet avec des images.

Rédiger la procédure d’enregistrement de l’interaction du jeu pour la vidéo de documentation.

Rédiger la procédure de fermeture du projet.

Enregistrer l’interaction avec l’installation pour la vidéo de documentation.

#### Mardi

Être responsable de l’ouverture de l’installation.

Enregistrer l’interaction des visiteurs avec l’installation pour la vidéo de documentation.

#### Mercredi

Enregistrer l’interaction des visiteurs avec l’installation pour la vidéo de documentation.

Contribuer à la surveillance de l’installation lors de l’exposition.

Apporter quelques corrections à la vidéo de documentation :

- Ajouter la partie échec
- Corriger le visuel des parties obscures
- Rectifier l’orthographe des sons

#### Jeudi

Être responsable de l’ouverture de l’installation.

Enregistrer le visuel ainsi que l’interaction du joystick et ses effets dans l’environnement.

Corriger les fautes d’orthographe dans le journal de bord.

#### Vendredi
