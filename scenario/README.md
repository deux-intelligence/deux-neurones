# Scénario

Cette section présente le scénario de l'interactivité du projet.

## Scène 1

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Bouger une des commandes | L'interacteur appuie sur un bouton ou fait pivoter un joystick ou le volant. | Des déchets commencent à couler du haut de l'écran vers le fond de l'océan où il y a un tas de déchets. | Une musique sombre d'ambiance commence à jouer. | Démarrage du jeu et passage à la scène 2. |

## Scène 2 

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Bouger le volant sous-marin | L’interacteur fait pivoter à gauche ou à droite le volant sous-marin. | Le modèle 2D du paysage océanique à 360 degrés, au centre duquel se trouve la caméra, pivote sur lui-même dans la même direction que le volant. | Un son de mouvement d’eau et de bulles est activé jusqu’à ce que le volant ne soit plus pivoté. | L’installation change la rotation du paysage océanique. |
| Bouger un joystick | L’interacteur fait rotationner le joystick sur les axes x et y. | Un bras mécanique muni d’un aspirateur se déplace dans les positions x et y à l’écran dans la même direction que le mouvement du joystick. | Un son de mouvement de machine se fait entendre lorsque le joystick est rotationné. | L’installation synchronise la position (x, y) de l’aspirateur avec celle du joystick. |
| Appuyer sur un bouton | L’interacteur appuie sur l’un des boutons rouges situés à côté d’un joystick. | Une animation d’aspiration de l’aspirateur s’active à l’endroit où se trouve l’aspirateur. | Un son mécanique s’active jusqu’à la fin de l’animation. | Activation de l’animation d’aspiration. |
| Attraper un déchet | L’aspirateur doit être à la même position que le déchet lorsque le bouton est appuyé. | Une animation d’aspiration de l’aspirateur s’active et aspire le déchet, qui n’est plus visible. | Un bruit de bouteille en plastique se joue jusqu’à la fin de l’animation de la pince. | Activation de l’animation d’aspiration et disparition d’un déchet. |
| Détection des objets déchets | Plus aucun déchet n’est détecté au fond de l’océan (sur le sol). | La couleur de l’océan devient plus claire et le nombre de créatures de poisson et de baleines augmente, avec à la fin l’apparition d’une tortue. | Changement de la musique d’ambiance pour une musique plus douce et joyeuse. | Fin de cycle – passage à la scène 3 |

## Scène 3 

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Quitter | Aucune des commandes n’est touchée pendant 4 minutes. | Les objets déchets arrêtent de couler avec l’arrêt de la duplication de ces objets à l’extérieur de l’écran, en haut de l’écran, et le visuel du jeu redevient celui de la scène 1. | Plus aucune musique ni aucun son n’est joué. | Passe à la scène 1 |