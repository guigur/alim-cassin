# alim-cassin
## Présentation
Ce PCB est un shield pour Arduino UNO.

Son but principal est de fournir à partir d'une batterie externe un rail **7V** très propre au régulateur linéaire de l'Arduino tout en générant également une alimentation **5V** pour alimenter un servomoteur. L'alimentation externe peut être coupée du système grâce au connecteur JST-XH3 où un bouton d'arrêt d'urgent NC se doit être connecté.

En découplant les alimentations, cela évite les resets intempestifs de l'Arduino lors d'efforts du servomoteur.

La version 2 du montage dispose d'un connecteur JST-XH4 compatible Groove afin d'y connecter un périphérique externe (dans notre cas un module bluetooth).
Un pont diviseur de tension est connecté sur le pin A0 permet également de mesurer la tension d'entrée jusqu'à 14V.

Enfin des LEDs permettent de visualiser l'état des rails d'alimentation.


## Schéma électrique
![schematic](https://github.com/guigur/alim-cassin/blob/main/images/cassin_pwr2.png "Schéma électrique du PCB")

## Rendu 3D
![3D render of PCB](https://github.com/guigur/alim-cassin/blob/main/images/3d_kicad.png "Rendu 3D du PCB")

## Le PCB (Prototype)
![Front of PCB](https://github.com/guigur/alim-cassin/blob/main/images/front.jpg "Face du dessus du PCB")
![Back of PCB](https://github.com/guigur/alim-cassin/blob/main/images/back.jpg "Face du dessous du PCB")

