J’ai conçu la simulation d’un robot hybride, à la fois roulant et volant, destiné à l’inspection automatisée d’un avion en hangar. Ce projet part d’un besoin évoqué lors de mon stage à la Direction de la Maintenance Aéronautique d’Air Algérie : éviter aux techniciens l’usage d’échelles ou le démontage de panneaux pour inspecter la structure d’un aéronef. Le robot, équipé d’une caméra, longe le fuselage de façon autonome, repère les défauts par traitement d’image (OpenCV), photographie chacun d’eux et génère un rapport d’inspection. Il dispose de deux modes de déplacement : le roulage au sol et le vol, qui lui permet de décoller, de franchir un obstacle puis de reprendre sa route.

En cours de développement : réunion de tous les éléments dans un seul monde Gazebo, publication de la position du robot et régulation de la hauteur. Extension optionnelle : exploration d'un demi-avion avec un capteur de distance.

Outils : ROS 2 Jazzy, Gazebo, Python, OpenCV.

## Contenu du dépôt
- 01_Cahier_des_charges : cahier des charges (jalon 1)
- 02_Conception_architecture : conception et architecture (jalon 2)
