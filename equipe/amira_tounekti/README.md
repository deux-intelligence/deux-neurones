# Amira Tounekti

![](amira.jpg )


### Semaine 1

- Faire la partie concept du site du projet (aspects visuels, palette de couleurs, médias de référence et scénarimage)
- Concevoir la page d’accueil en choisissant l’image, puis en rédigeant la description et le résumé
- Créer les fichiers de travail : Unity, Pure Data et Visual Studio Code
- Programmer dans Visual Studio Code la communication de l’encodeur, du joystick et du Key Unit vers Unity via Pure Data

### Semaine 2

- Commencer à rédiger le journal de bord
- Coder dans Unity la génération aléatoire des déchets à récolter, l’animation des déchets qui tombent, la disparition des déchets sous la condition de l’activation du bouton et de la collision avec l’aspirateur, l’accumulation des déchets avec une limite définie par un compteur, la disparition des déchets après un certain temps au sol, ainsi que la rotation de la caméra à l’aide d’un encodeur
- Création d’un compteur pour le nombre de déchets dans la scène
- Commencer à mettre certains assets et animations
- Coder le déplacement de l’aspirateur à l’aide du joystick autour de la comera au centre du jeu.
- Documenter le code dans Unity

### Semaine 3

- Finaliser la maquette 1 (prototype du jeu – programmation dans Unity)
- Construire un contenant test des éléments (joystick, Keys Unit et encodeur)
- Implanter la première version animée des assets visuels dans Unity pour la maquette 1
- Commencer à effectuer quelques corrections de code après les commentaires des professeurs

### Semaine 4

- Mettre en place le volant avec l’encodeur
- Commencer la construction du boîtier du panneau de contrôle
- Classer les fichiers techniques de l’Arduino (Visual Studio Code, Unity et Pure Data)
- Apporter les modifications de la maquette 1 pour réaliser la maquette 2

### Semaine 5

- Implanter les nouveaux médias d’animation et les visuels dans Unity
- Implanter les sons dans Unity avec leurs interactions respectives dans le code, ainsi que les musiques d’ambiance
- Mettre les joysticks, les boutons et le volant dans le panneau de contrôle
- Réaliser le montage de la bande-annonce
- Créer le logo du projet « Océan Rouge »

### Semaine 6

- Réaliser les finitions de la maquette 2
- Rédiger la moitié du dossier de presse de description à bande-annonce
- Ajouter les sons manquants dans Unity après la remise de la maquette 2

### Semaine 6.5

- Réaliser le montage de la vidéo de documentation
- Remplacer les médias par les versions corrigées et optimisées

### Semaine 7

- Effectuer le contrôle qualité et corriger les éventuelles erreurs dans Unity, Visual Studio Code, Pure Data et sur le boîtier du panneau de contrôle
- Refaire la documentation du code dans Unity

### Semaine 8

- Présenter l’installation
- Finaliser le journal de bord

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
- Finaliser les corrections des semaines des tâches hebdomadaires dans l’équipe
- Commencer à rédiger le journal de bord des tâches quotidiennes
- Finaliser les corrections du concept du site du projet Océan Rouge
- Coder le déplacement de l’aspirateur (cube 3D) avec le joystick de gauche à droite dans l’axe X et Y
- Faire le code du Keys Unit dans Unity pour que Unity reçoive les données du bouton
- Coder le déplacement des déchets (sphère 3D) qui tombent vers le bas de l’écran
- Mettre en place la détection de collision entre l’aspirateur (cube 3D) et les déchets (sphère 3D) dans Unity
![](semaine2-3.png)

#### Mardi
- Faire tourner la caméra sur elle-même avec l’encodeur dans l’axe Y
- Coder la disparition des déchets sous la condition de l’activation du Keys Unit et de la collision entre l’aspirateur et le déchet
- Coder la création de déchets aléatoires suivant la forme d’un cercle autour de la caméra
![](semaine2-5.png)
![](semaine2-2.png)

#### Mercredi
- Coder le mouvement de l’aspirateur pour qu’il tourne autour de la caméra et se déplace librement sur l’axe Y
- Ajout d’assets de test : un sprite 2D de déchet placé dans la sphère 
- Ajout d’un sprite 2D d’aspirateur animé se déplaçant avec le joystick pour correspondre à l’emplacement du cube
![](semaine2-1.png)

#### Jeudi
- Mettre en place un compteur pour connaître le nombre de déchets présents dans la scène 
- Coder une limite de mouvement sur l’axe Y pour l’aspirateur
- Coder la destruction des déchets après un certain délai, déclenchée lorsque le déchet dépasse une limite sur l’axe Y
![](semaine2-8.png)

#### Vendredi
- Faire la documentation du code dans Visual Studio Code et Unity
- Coder une limite au nombre de déchets présents dans la scène, de sorte qu’après un certain nombre la génération aléatoire de déchets s’arrête
- Coder le déclenchement de l’animation du sprite 2D (aspirateur) avec le bouton (Keys Unit)
- Créer une nouvelle version du jeu Unity plus propre, avec des fichiers et dossiers mieux organisés et nommés
![](semaine2-9.png)

### Semaine 3

#### Lundi
- Nettoyage des scripts en simplifiant la logique de mouvement de l’aspirateur et de la bouteille
- Classement plus propre des fichiers et des dossiers dans Unity
- Remplacement de l’asset de test du déchet par la nouvelle version animée dans Unity et ajout du code qui active l’animation du déchet avant qu’il soit détruit au sol
- Ajout d’une ligne de code dans le script DechetsScript pour que le déchet fasse toujours face à la caméra
![](semaine3-3.png)

#### Mardi
- Faire en sorte que, lorsque la bouteille touche le sol, l’animation de détérioration du déchet commence
![](semaine3-2.png)

#### Mercredi
- Construire la boîte qui contiendra le bouton, l’encodeur et le joystick
- Replacer l’aspirateur devant la caméra pour obtenir un mouvement plus réaliste
![](semaine3-1.jpg)
![](semaine3-4.png)

#### Jeudi
- Faire des corrections sur la maquette 1 avant la présentation aux portes ouvertes

#### Vendredi
- Ajouter les sprites animés des algues foncées et les disposer dans l’environnement autour de la caméra
- Coder une animation plus réaliste de la chute de la bouteille au fond de l’océan en faisant pivoter la bouteille lorsqu’elle touche le sol
- Mettre le dossier du projet sur GitHub

[Commit 6 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/3dc9bcb5ac0f17a6341bc35a3e953b4980fc4d71)

[Commit 6 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/7ba1d5821b0d685c47645805c3b1f4ea8ee11a56)

### Semaine 4

#### Lundi
- Ajout des algues foncées qui se retirer vert le bas depandament du compteur
![](semaine4-2.png)
[Commit 9 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/24ff9bcdec82ba5f985f32a0a3762dc61c2643b9)

#### Mardi
- remplacer la bouteille 2d par la bouteille 3d sans animation
- remplacer le code de la chute du dechets par la graviter
- ajouter les sprites tortues anime avec leur deplacement autour du pivot
![](semaine4-3.png)
[Commit 10 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/584f1a8ee111453eedd0563acf03711560eaadf2)

#### Mercredi
- Coder la disparition des tortues vers le haut depandament du compteur
- Ajouter l’effet de pollution dans le paysage en fonction du compteur : les trois images PNG deviennent de plus en plus visibles, le panel devient de plus en plus visible, et le paysage devient de plus en plus foncé
- Faire en sorte que la vitesse de la camera soit plus fluide et quel augment avec la vitessse de toure de l'encodeur
![](semaine4-4.png)
[Commit 11 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/6a99b3b959efa9846cf69a9c22fe2dbe8ae45428)

#### Jeudi
- Faire en sorte dans Visuel Studio Code que l'encodeur reseptionne mieux les changements
- Mettre le nouveau bras kinesthésique et coder son mouvement au point d’ancrage ainsi que son mouvement de droite à gauche de l’aspirateur
- Remplacement de l’activation de l’animation d’aspiration de l’ancien aspirateur par celle du nouvel aspirateur kinesthésique.
- Creation d'un groupe de conversion sur teams pour tous les membre du comité.

[Commit 12 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/26d0a8f2f5a5c4d5ffe7335aa2df3d1ae5fd41a2)

#### Vendredi
- Planification pour la construction 
- Alignement de l'aspirateur 2D avec le viseur 3D (cube)
- Ajouter des poissons avec leurs mouvements autour du point d’ancrage et définir leurs conditions d’apparition
- Mis en place de la prochaine rencontre du commité deambulation de la semaine 5 pour Lundi.
[Commit 13 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/5ece87617ceacbbe9476f30ef2ca39d01a2cf677)


### Semaine 5

#### Lundi
- Ajout de deux autre dechets (shampoing et cannette) pour avoit trois dechets qui apparaise dans la scene aleatoirement
- Ajout des algues clair dans la scene avec leurs condition d'apparition
- Ajout des sons (atterisage de la bouteille, aspiration, disparition du dechet, sons d'ambiance sombre) dans la scene avec leurs condition d'apparition
- Demarrage de l'impression 3d du soutiens pour le cartel pour le comité deambulation.
[Commit 15 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/d208df99de2060ccaf813d08c3b953f13f594a61)
[Commit 16 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/6fb30273fe47aea0a7eec6daef94a2f12c6e7b61)

#### Mardi
- Modification du viseur qui se déplace en cercle, pour un laser sous forme d’un cylindre allongé suivant les axes X et Y, allant de l’aspirateur jusqu’au déchet.
- Codage de la modification de la position et de la taille du déchet lorsqu’il est aspiré, afin qu’il entre correctement dans l’aspirateur.
- Prise de mesures de la largeur et de la longueur du bois pour le panneau de contrôle mince et epais et prise de mesure pour le cadre de l’écran, puis découpe pour correspondre aux nouvelles dimensions.
![](semaine5-1.jpg)
[Commit 17 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/a412c8211e8cd62da959f4d31b3935c4733c8f0a)

#### Mercredi
- Prise de mesures du cercle et découpe du panneau en bois mince pour faire passer le joystick dans un trou rond centré au milieu.
- Prise de mesures d’un carré suffisamment large pour laisser passer le joystick dans le panneau en bois épais.
- Codage des données du joystick dans Unity afin d’adapter le code aux nouvelles informations apportées par le nouveau joystick 4D (rotation de la caméra, mouvement de l’aspirateur et bouton déclenchant l’aspiration).
- Remplacement des sons d’aspiration et de mouvement du sous-marin par une version corrigée et améliorée.
![](semaine5-2.jpg)
[Commit 18 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/b1d10dfece9aef8c50e0028fa5738ac01a98a891)
[Commit 18 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/f785a2112240cfd638494b09d99916ea67f00c36)

#### Jeudi
- Calcul de la position et perçage des quatre vis qui maintiendront le joystick (du haut vers les trous en bas du joystick).
- Calcul de la position des trous sur le panneau de contrôle mince et perçage pour pouvoir l’aligner plus tard avec le panneau de contrôle épais et l’arcade.
- Mise en place de la peinture en noir du panneau de contrôle mince.
- Codage d’une limitation du nombre de fois où l’animation et le son d’aspiration, ainsi que la destruction du déchet, peuvent se produire, en fonction du temps pendant lequel le bouton est resté appuyé (1 fois pour chacun).
- Création d’un nouveau pivot vers lequel se dirigera le déchet lorsqu’il sera aspiré ; ce nouveau GameObject (pivotAspiration) remplacera l’aspirateur.
- Redesign d’une nouvelle version du logo de notre projet pour la maquette 2.
![](semaine5-3.jpg)
![](logo.png)
[Commit 19 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/10ee4224ade88f39c4101ba76502f27b6f56d1fc)

#### Vendredi
- Positionner le joystick dans le panel de contrôle mince et ajuster sa façade. Ajouter également la façade du terminal Arduino sous le panel de contrôle épais. Enfin, assembler le tout avec le cabinet d’arcade.
- Quelques réparations sur le maximum de déchet et sur le visuel dans le canvas, pour ensuite réaliser un build et tester dans l’arcade.
- Faire le montage vidéo et sonore de la bande-annonce.
[Commit 20 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/673c92642ec7dce395c018bef4319979564d1649)
[Commit 20 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/65911ff4c85998f2590e3baed573605e7c9141e4)
[Commit 20 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/cb0bb4ee128fa264fea991c9ae7fcf8a8b7440a2)
[Commit 20 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/8a7a8ddd178fa243cac1cd78895a6980f6d02a2c)
![](semaine5-4.jpg)
![](montage-video.png)


### Semaine 6

#### Lundi
- Fin des 6 impression 3d du soutiens pour le cartel pour le comité deambulation.
- Ajouter des descriptions dans la bande-annonce.
- Remplir la partie « Histoire » du dossier de presse.
- Intégrer la bande-annonce à l’accueil et au dossier de presse.
- Se renseigner sur le déroulement du design du cartel géré par Yannick et Rafael. Communiquer la finalisation de l’impression des supports pour les cartels.
[Commit 23 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/7af5a3b27df17c5cc6faa4da5610afff3b11ca1a)
![](semaine6-1.jpg)
![](montage-video2.png)

#### Mardi
- Ajout d'une limitation du nombre de déchets dans la scène.
- Build du projet pour la maquette 2.
- Creation de la scene accueil avec trois panel pour les instructions du joystick.
[Commit 24 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/9ceebf73aaed3532b6e4edf8f426ca8375bd321b)
![](semaine6-1.jpg)

#### Mercredi
- Mise en place de chaque sprite de l'instruction du joystick dans un panel.
- Codage de la desactivation des panel si le mouvement montrer sur le sprite pour chaque panel est realiser sur le joystick.
- Ajout du changement de scene vers ocean-rouge lorsque la dernierre instruction du dernier panel est realisé sur le joystick.
- Codage d'une progression de la difficulter en reduisant le delay entre la creation de bouteille depandament du compteur.
- Réparation de la zone morte en l'augmentant pour la rotation du joystick.
- Ajout des panels gagner et perdre avec leur script ou est coder leur condition d'apparition qui depent du compteur.
- Codage du limite du nombre de dechet qui peut etre aspirer a la fois.
- Retirer l'ecran de l'arcade pour plus tard pouvoir le changer.
- Mis en place de la prochaine rencontre du commité deambulation de la semaine 6 pour vendredi.
- Creation et envois au membre du commit Déambulation un formulaire a remplir pour les cartel de leur equipe
![](semaine6-2.png)
![](semaine6-3.png)
[Commit 25 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/9b0a462a6becd5d7de485067d9252b168f5de243)
[Commit 25 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/3283566670f738f3591d238c08b401f33139d897)

#### Jeudi
- Augmentation de la durer du dechet au sol avant qu'il soit detruit.
- Deboguage du compteur des dechets pour le realigner avec le nombre real de dechets qui se trouve dans la scene.
- Envois et creation du formulaire des information a mettre sur le cartel de chaque equipe pour le commiter de deambulation
[Commit 26 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/9d2090bf97b851bdde7d0a9f52a0b1455900e3e7)


#### Vendredi
- Placement de trois autres plantes dans la scène de jeu et codage de leurs conditions d’apparition en fonction du compteur, en les faisant se mouvoir sur l’axe Y.
- Placement de deux autres créatures marines (crabes et baleines) dans la scène, codage de leurs mouvements en cercle autour de la caméra et codage de leurs conditions d’apparition en fonction du compteur, en les faisant se mouvoir sur l’axe Y.
[Commit 27 Fevrier du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/4cffcbae96da0e89a950a41cbfc4a73deeed44d3)

### Semaine 6.5

#### Lundi
- Vérification de la compatibilité du nouveau écran dans l’arcade.

#### Mardi
- Déplacer avec Antoine le support de l’écran pour adapter l’arcade au VESA du nouveau écran.
- Codage des déchets prédéfinis pour qu’ils soient déjà au sol au début du jeu.
- Ajout d’une animation de transition pour l’apparition ou la disparition d’une scène, avec un panel passant de l’opacité 0 à 1.
- Ajout de deux variantes supplémentaires pour les sons : chute de déchet au sol, aspiration et absorption de déchet, avec codage de la condition d’apparition aléatoire entre les variantes.
[Commit 3 Mars du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/8d1fc89c3a6d4815b2701a6848f25d54f83eac46)

#### Mercredi
- Modification de la version du plan des installations de Radhouane pour une version final
![](semaine6_5-1.png)

#### Jeudi
- Reparation des marge du cartel et legeure modifiation du designs pour chaque cartel.
- Ajout des informations des projets pour chaque cartel
![](semaine6_5-3.png)

#### Vendredi
- Ajout des sons du crabe lorsqu’il se déplace pour chaque crabe, avec la condition qu’ils ne jouent que lorsque le compteur est en dessous d’un certain chiffre.
- Ajout des sons de la baleine, avec la condition qu’ils ne jouent que lorsque le compteur est en dessous d’un certain chiffre.
- Mise en place de l’animation de la baleine dans les panels "Gagné" et "Perdu", avec un déplacement le long de l’axe des X.
[Commit 6 Mars du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/0d69bb51431c2253acc0826386fbc5e85cf745e6)

### Semaine 7

#### Lundi
- Codage du changement entre le texte du panel "Tu as gagné" ou du panel "Tu as perdu" avec les crédits
- Remplacement de l’arrêt complet du jeu lorsque le joueur gagne ou perd par l’arrêt uniquement des sons du jeu, à l’exception du son d’ambiance correspondant à la victoire ou à la défaite
- Changement de l’audio des crabes avec la nouvelle version
- Ajout de l’animation de la bouteille dans les crédits du panel « perdu » du jeu pour remplacer la baleine
- Ajout d’une transition lorsque la scène change à la fin du jeu, avec un panel de transition qui passe au noir
- Modification des données d’apparition de chaque plante et créature en fonction du compteur, en tenant compte également de la pollution
[Commit 9 Mars du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/c1d0fa5d377ec815c3f2f08f8f6f679bc87d5926)
[Commit 9 Mars du projets ocean-rouge](https://github.com/deux-intelligence/dossier-du-projet/commit/d94d400805cdb9eec70bba20288af625f750bb37)

#### Mardi
- Peinture de la deuxieme couche du panel de controle de l arcade
- Trouer les deux troues a gauche de l arcade pour mettre les vise du panel de control
- Ajustement du sons pendant que la panel gagner ou perdu apparait pour fair arreter les sons que provoque l utilisation du joystick
- Correction du designe et de la taille du cartel


#### Mercredi
- Réglage des sons dans l’accueil pour qu’ils ne se coupent pas et que le code attende la fin d’un son avant d’en lancer un nouveau
- Mise en place d’une introduction au début dans l’accueil pour présenter le titre et une partie du jeu en fond. Pour cela, j’ai mis le titre du jeu avec un fond vidéo du jeu qui joue. Après un certain temps, la vidéo et le titre passent en opacité 0 via une animation

#### Jeudi
- Communiquer avec la vie étudiante et l’AGEM pour mettre sur BabiArt les affiches de l’emplacement du studio.
- Impression de l’affiche de l’emplacement des installations et de l’emplacement du grand studio.
- Mise en place des codes QR de chaque équipe dans leur cartel.
- Correction des fautes d’orthographe dans le jeu.
- Modification de l’intro pour que le manuel du bouton du joystick soit dessus et que, lorsque le bouton est appuyé, l’intro disparaisse.

#### Vendredi

### Semaine 8

#### Lundi

#### Mardi

#### Mercredi

#### Jeudi

#### Vendredi