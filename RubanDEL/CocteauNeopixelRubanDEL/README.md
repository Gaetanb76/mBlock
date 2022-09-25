***********************************************
*****  Extension CocteauNeopixelRubanDEL  *****
***********************************************

Cette extension pour mBlock v.3.4.12 permet de commander un ruban de DEL RVB de type Makeblock
Le ruban a 3 broches qui seront reliées aux VCC, GND et une PWM

L'extension utilise la bibliothèque Adafruit_NeoPixel.h

Description des blocs :
- initialiser le ruban DEL  : broche ; nombre de DEL
- allumer une DEL en déterminant  son numéro sur le ruban (0 = première DEL) et sa couleur RVB
- Allumer toutes les DEL avec une couleur RVB
- Éteindre toutes les DEL
- Régler la luminosité des DEL

