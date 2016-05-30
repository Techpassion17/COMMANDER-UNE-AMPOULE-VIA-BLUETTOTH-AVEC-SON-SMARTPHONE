# COMMANDER-UNE-AMPOULE-VIA-BLUETTOTH-AVEC-SON-SMARTPHONE
le but de ce montage est de commander une ampoule avec son smartphone 

***** 1ere étape

décompresser et copier dans le dossier libraries contenu dans le dossier d'installation de arduino le mien est:
C:\ Program Files \ Arduino \ libraries

*****  2ème étape

réaliser le cablage 

*****  3ème étape 

Télécharger  et installez l'application Arduino Bluetooth Control sur votre smartphone 
voici le lien de téléchargement:    https://play.google.com/store/apps/details?id=com.broxcode.arduinobluetoothfree&hl=fr

*****  4ème étape 
déconnectez les fils qui sont conncté au RX et TX de la carte arduino avant de charger le code sinon cela mettra une erreure de compilation
deconnectez les deux fils 
Maintenant chargez votre code source sur la carte arduino
Maintenant reconnectez les deux fils a la carte arduino

*****  5ème étape 
 allumez le montage la led de votre module bluetooth clignote incessement.connectez votre smartphone au module bluetooth maintenant la led de votre module bluetooth doit clignoter une fois et s'éteindre.
 
 **** 6ème étape 
 lancez l'application et autorisez l'application a utiliser le bluetooth
 apuyez sur les flèches en cercles de réactualisation situez en haut a droite avant la roue de paramètre
 selectioner le module bluetooth HC-05
 lancez le terminal
 envoyez le chiffre 1 l'ampoule s'allume
 envoyez le chiffre O l'ampoule s'éteint
 dans le même temps ouvrez votre moniteur série vous aurez le statut des lampes
