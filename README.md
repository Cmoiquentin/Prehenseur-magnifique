# Prehenseur-magnifique
Préhenseur réalisé en impression 3D (PLA) utilsant un système de Pignon-Crémaillère.

<img width="361" height="438" alt="Prehenseur" src="https://github.com/user-attachments/assets/591309f1-cd3b-4930-a67a-29bbb3ec757d" />

Ce préhenseur est un système de prise mécanique actionné par un servomoteur Dynamixel XL320, conçu pour s'adapter sur un robot collaboratif Niryo NED. Son fonctionnement repose sur la transmission du mouvement rotatif du servomoteur en un mouvement de fermeture/ouverture symétrique des deux doigts de préhension. Lorsque le servomoteur tourne dans un sens, les doigts se rapprochent et saisissent l'objet cible ; dans le sens inverse, ils s'écartent et relâchent la pièce. Le XL320 communique via le protocole Dynamixel Protocol 2.0 sur un bus série half-duplex TTL, ce qui permet un contrôle précis de la position, de la vitesse et du couple de serrage directement depuis le contrôleur du Niryo NED, qui intègre nativement ce protocole.

Référence : Dynamixel XL320 — ROBOTIS
Tension d'alimentation : 5 V (fournie par le bus interne du Niryo)
Communication : protocole Dynamixel Protocol 2.0, bus TTL half-duplex
Couple de décrochage : 0,39 N·m à 5 V
Connecteur : JST 3 broches (Power / GND / Data)
<img width="1106" height="785" alt="Capture d’écran 2026-06-17 120423" src="https://github.com/user-attachments/assets/30a96f97-d8df-4722-b1bf-9f3a297776f2" />
