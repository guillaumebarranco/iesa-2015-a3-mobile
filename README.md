# iesa-2015-a3-mobile
Cordova first time test IESA

10/04/2015 > Première installation de Cordova suivie par la première utilisation de l'émulateur IOS et de ses fonctionnalités basiques. J'ai un Iphone sur mon ordi désormais.

Accès au splash-screen, connection status, select picture from gallery, détecter changement orientation, effet images, geolocalisation, contacts du tel, store information on tel, appareil photo du tel.

Navigation flow (écrans de l'app avant de faire l'appli)

1) Splashs screens
2) Icônes

Installation du plugin des splashs.

Par défaut, les splashs et icones pour chaque appareil IOS se trouvent dans la plateform IOS (mais peut être changé dans le config.xml de l'appli et ainsi on peut prendre les images d'où on veut)

Bug de compilation résolu en supprimant une image en trop (que j'avais rajoutée) dans le dossier splashs (bizarre)

Intégration du plugin device qui affiche toutes les infos relatives au device (logique) tels que version cordova, modèle, plateforme, unique id et version.

Apprentissage des plugins network connection et contacts.

Network connection est vraiment utile car grâce à lui on va pouvoir gérer la connection et non connection de l'utilisateur et agir en fonction de la réponse (plus de fonctionnalités pour un connecté mais pas de bugs pour un non connecté)

La gestion des contacts peut être utile également (et niveau sécurité il y a une autorisation donc c'est cool)