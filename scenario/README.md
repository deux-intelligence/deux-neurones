# Scénario

Cette section présente le scénario de l'interactivité du projet.

## Scène 1

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Debut | L’interacteur doit avoir perdu ou gagner. | L intro qui possede le titre du jeux joue pendant un certain temps avant  | Une sons d'ambiance sombre commence à jouer. | Démarrage du jeu et passage à la scène 2. |

## Scène 2

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Debut | L’interacteur doit avoir perdu ou gagner. | Des déchets commencent à couler du haut de l'écran vers le fond de l'océan où il y a un tas de déchets. | Une sons d'ambiance sombre commence à jouer. | Démarrage du jeu et passage à la scène 2. |

## Scène 3

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Debut | L’interacteur doit avoir perdu ou gagner. | Des déchets commencent à couler du haut de l'écran vers le fond de l'océan où il y a un tas de déchets. | Une sons d'ambiance sombre commence à jouer. | Démarrage du jeu et passage à la scène 2. |

## Scène 4 

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Tourner le joystick du sous-marin | L’interacteur fait pivoter à gauche ou à droite le joystick du sous-marin. | La caméra tourne sur elle-même au centre grâce au joystick du modèle 2D du paysage océanique à 360 degrés. | Un son de pulsion d’eau et mécanique est activé jusqu’à ce que le joystick ne soit plus pivoté. | L’installation change la rotation de la caméra. |
| Bouger un joystick | L’interacteur fait tourner le joystick sur les axes X et Y. | Un bras mécanique muni d’une pompe à déchets se déplace dans les positions X et Y à l’écran, dans la même direction que le mouvement du joystick. | Un son de mouvement de machine se fait entendre lorsque le joystick est tourné sur les axes X et Y. | L’installation synchronise la position (X, Y) de la pompe à déchets avec celle du joystick. |
| Appuyer sur un bouton | L’interacteur appuie sur un bouton situé sur le joystick. | Une animation d’aspiration de la pompe à déchets s’active à l’endroit où se trouve celui-ci. | Un son d’aspiration s’active jusqu’à la fin de l’animation. | Activation de l’animation d’aspiration. |
| Attraper un déchet | La pompe à déchets doit être à la même position que le déchet lorsque le bouton est appuyé. | Une animation d’aspiration de la pompe à déchets s’active et aspire le déchet, qui n’est plus visible. | Un bruit d’aspiration de la pompe à déchets et du déchet aspiré se joue jusqu’à la fin de l’animation de la pompe à déchets et à la disparition du déchet. | Activation de l’animation d’aspiration et disparition d’un déchet. |
| Détection plus de déchets | Plus en plus de dechets est detecter au fond de l’océan. | La couleur de l’océan devient plus opaque et le nombre de créatures et de plantes marines baisse (poissons, tortues et algues). | Sons d ambiance mélodieuse et calme retirer pour ne laisser que les sons d ambiance sombre. | Fin de cycle – passage à la scène 3 |
| Détection moins de déchet | De moins en moins de déchets est détecté au fond de l’océan. | La couleur de l’océan devient plus claire et le nombre de créatures et de plantes marines augmente (poissons, tortues et algues). | Ajout à la sons d'ambiance sombre d’une sons mélodieuse et calme. | Fin de cycle – passage à la scène 3 |

## Scène 5 

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Quitter gagner | 60 déchets est détecté au fond de l’océan. | Panel perdu apparait devant l ecran avec une animation de credit | Plus aucun sons n’est joué a part les sons d ambiance sombre. | Passe à la scène 1 |
| Quitter perdu | 0 déchet est détecté au fond de l’océan. | Panel gagner apparait devant l ecran avec une animation de credit | Plus aucun sons n’est joué a part les sons d ambiance calme. | Passe à la scène 1 |