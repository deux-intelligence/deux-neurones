# Scénario

Cette section présente le scénario de l'interactivité du projet.

## Scène 1

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Bouger une des commandes | L’interacteur appuie sur un bouton, fait pivoter un joystick ou fait tourner le joystick. | Des déchets commencent à couler du haut de l'écran vers le fond de l'océan où il y a un tas de déchets. | Une musique sombre d'ambiance commence à jouer. | Démarrage du jeu et passage à la scène 2. |

## Scène 2 

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Tourner le joystick du sous-marin | L’interacteur fait pivoter à gauche ou à droite le joystick du sous-marin. | La caméra tourne sur elle-même au centre grâce au joystick du modèle 2D du paysage océanique à 360 degrés. | Un son de pulsion d’eau et mécanique est activé jusqu’à ce que le joystick ne soit plus pivoté. | L’installation change la rotation de la caméra. |
| Bouger un joystick | L’interacteur fait tourner le joystick sur les axes X et Y. | Un bras mécanique muni d’un aspirateur se déplace dans les positions X et Y à l’écran, dans la même direction que le mouvement du joystick. | Un son de mouvement de machine se fait entendre lorsque le joystick est tourné sur les axes X et Y. | L’installation synchronise la position (X, Y) de l’aspirateur avec celle du joystick. |
| Appuyer sur un bouton | L’interacteur appuie sur un bouton situé sur le joystick. | Une animation d’aspiration de l’aspirateur s’active à l’endroit où se trouve celui-ci. | Un son d’aspiration s’active jusqu’à la fin de l’animation. | Activation de l’animation d’aspiration. |
| Attraper un déchet | L’aspirateur doit être à la même position que le déchet lorsque le bouton est appuyé. | Une animation d’aspiration de l’aspirateur s’active et aspire le déchet, qui n’est plus visible. | Un bruit d’aspiration de l’aspirateur et du déchet aspiré se joue jusqu’à la fin de l’animation de l’aspirateur et à la disparition du déchet. | Activation de l’animation d’aspiration et disparition d’un déchet. |
| Détection des objets déchets | Plus aucun déchet n’est détecté au fond de l’océan (sur le sol). | La couleur de l’océan devient plus claire et le nombre de créatures et de plantes marines augmente (poissons, tortues et algues). | Ajout à la musique d'ambiance sombre d’une musique mélodieuse et calme. | Fin de cycle – passage à la scène 3 |

## Scène 3 

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Quitter | Aucune des commandes du joystick n’est touchée pendant 4 minutes. | Les objets déchets arrêtent de couler avec l’arrêt de la duplication de ces objets à l’extérieur de l’écran, en haut de l’écran, et le visuel du jeu redevient celui de la scène 1. | Plus aucune musique ni aucun son n’est joué. | Passe à la scène 1 |