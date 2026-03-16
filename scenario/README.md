# Scénario

Cette section présente le scénario de l'interactivité du projet.

## Scène 1

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Débuter  | L’interacteur doit avoir perdu ou gagné, ou le jeu doit avoir été démarré. | Le titre du jeu est affiché avec un fond vidéo montrant à quoi ressemble le jeu. À côté du titre, une animation du joystick montre l’interaction avec le bouton. | Aucun son n’est joué. | Passage à la scène 2. |
| Appuyer | L’interacteur doit avoir appuyé sur le bouton du joystick. | Une animation du joystick montrant sa capacité à pivoter sur fond bleu clair remplace l’ancien visuel. | Aucun son n’est joué. | Passage à la scène 2. |

## Scène 2

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Pivoter joystick | L’interacteur doit avoir fait pivoter le joystick. | Une animation du joystick montrant sa capacité à bouger sur les axes X et Y sur un fond bleu plus foncé remplace l’ancien visuel. | Aucun son n’est joué. | Passage à la scène 3. |

## Scène 3

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Bouger joystick | L’interacteur doit déplacer le joystick sur les axes X et Y. | Le visuel du jeu montre un océan (sable et montagnes) rempli de déchets au fond, avec une eau troublée et un écran partiellement saleté. | Les sons d’ambiance sombre sont joués. | Passage à la scène 4. |

## Scène 4 

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Tourner le joystick du sous-marin | L’interacteur fait pivoter le joystick du sous-marin vers la gauche ou la droite. | La caméra tourne sur elle-même au centre grâce au joystick du modèle 2D du paysage océanique à 360 degrés. | Un son de pulsion d’eau et mécanique est activé tant que le joystick est pivoté. | L’installation change la rotation de la caméra. |
| Bouger un joystick | L’interacteur déplace le joystick sur les axes X et Y. | Un bras mécanique muni d’une pompe à déchets se déplace sur les positions X et Y à l’écran, suivant le mouvement du joystick. | Un son de machine se fait entendre lors du déplacement du joystick sur les axes X et Y. | L’installation synchronise la position (X, Y) de la pompe à déchets avec celle du joystick. |
| Appuyer sur un bouton | L’interacteur appuie sur un bouton situé sur le joystick. | Une animation d’aspiration de la pompe à déchets s’active à l’emplacement de celle-ci. | Un son d’aspiration est joué jusqu’à la fin de l’animation. | Activation de l’animation d’aspiration. |
| Attraper un déchet | La pompe à déchets doit être à la même position que le déchet lorsque le bouton est appuyé. | Une animation d’aspiration de la pompe à déchets s’active et aspire le déchet, qui disparaît de l’écran. | Un bruit d’aspiration de la pompe à déchet est joué jusqu’à la fin de l’animation et à la disparition du déchet. | Activation de l’animation d’aspiration et disparition du déchet. |
| Détection de plus de déchets | De plus en plus de déchets sont détectés au fond de l’océan. | La couleur de l’océan devient plus opaque et le nombre de créatures et plantes marines diminue (poissons, tortues, algues). | Les sons d’ambiance mélodieuse et calme sont retirés, ne laissant que les sons d’ambiance sombre. | Fin de cycle – passage à la scène 3 |
| Détection de moins de déchets |De moins en moins de déchets sont détectés au fond de l’océan. | La couleur de l’océan devient plus claire et le nombre de créatures et plantes marines augmente (poissons, tortues, algues). | Les sons d’ambiance sombre sont complétés par des sons mélodieux et calmes. | Fin de cycle – passage à la scène 5 |

## Scène 5 

| Verbe Action | Condition/contexte | Effet visuel | Effet sonore | Effet interactif |  
| :------      | :----------------: | :----------: | :----------: | ---------------: |
| Quitter (gagné) | 60 déchets ont été détectés au fond de l’océan. | Le panel « Perdu » apparaît à l’écran avec une animation de crédits. | Aucun son n’est joué, à l’exception des sons d’ambiance sombre. | Passe à la scène 1 |
| Quitter (perdu) | 0 déchet n’a été détecté au fond de l’océan. | Le panel « Gagné » apparaît à l’écran avec une animation de crédits. | Aucun son n’est joué, à l’exception des sons d’ambiance calme. | Passe à la scène 1 |