# Nacelle-et-Commande-KAP-Arduino
Projet visant au développement d'une nacelle d'aérophotographie (embarquée par un cerf-volant) et de son boitier de de commande pour orienter l’appareil et déclencher depuis le sol.

En l'air :
- une arduino (micro ou nano)
- emeteur/recepteur radio + antenne (https://www.adafruit.com/product/3070)
- un capteur de pression pour faire altimètre (https://www.adafruit.com/product/1893)
- deux servomoteurs continus avec feedback pour le tilt et le pan (https://www.adafruit.com/product/1404)
- un micro servo pour la prise de vue (ou une impulsion si on a un canon bidouillé...)
- une carte de séparation de l'alimentation des servos et connexion en I2C (https://www.adafruit.com/product/815)
- batterie d'alimentation du circuit de commande
- batterie d'alimentation du circuit de puissance

Au sol :
- une arduino Uno
- émetteur/récepteur radio + antenne (https://www.adafruit.com/product/3070)
- un joystick 2 axes + clic pour la commande manuelle pan/tilt et le déclenchement (https://www.adafruit.com/product/245)
- un afficheur 7 segments pour les affichages (angles / altitude) (https://www.adafruit.com/product/879)
- batterie d'alimentation du circuit de commande
- éventuellement, des petits switchs pour déclencher séquences de programme d'autokap

Dans le futur :
- une mini camera+émetteur+batterie et un écran de retour vidéo+récepteur de chez bandgood... 
