Gestion des Caméras
=====================
- InputCam.ini et Maps & modes config.ini sont à charger (avec import) dans la settings projets de unreal (un dans la partie input et l'autre dans la partie Maps & modes ^^) 
- Les 4 cams se positionnent par rapport au sol donc il faut mettre BP_Floor dans la scene 
- BP_CamSwitch gère le changement de cam #flèche gauche et flèche droite (directionnelles)
- BP_GameControl nécessaire pour les contrôles (#mode de jeu avec input et co custom)
- On peut modifier dans BP_Floor les offset pour changer la vision, les angles peuvent être redéfini aussi selon, mais plus touchy (dans les BP des cams), vue en perspective
---
Les cams se positionnent à l'event beginPlay voilà ;)

Ps: la vue des cams était pas bonne parce que les données de rotation (hardcodées) ne se sauvegardent  pas avec le BP des cams mais avec avec la scene (comme le positionnement) #révélation xD #sorry
