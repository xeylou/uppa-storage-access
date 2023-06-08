# Pourquoi ce document ?

J'ai créé ce document pour montrer qu'il est possible de travailler sur une machine Debian à l'IUT, de modifier ce travail sur une machine Windows de l'IUT et de continuer de travailler depuis chez soit sur son ordi.

## Rappel sur le stockage des machines physiques
Les machines physiques sont montées avec un dual-boot Debian/Windows en réseau. 

Les sessions Debian sont synchronisées entre les machines physiques via leur `/home`. *Si une session Debian sur une machine physique télécharge ou édite des fichiers : ces changements sont visibles sur toute session Debian à l'IUT avec les mêmes identifiants.*

**L'état des sessions Windows n'est pas conservé entre les machines physiques, les modifications sont appliquées sur la machine physique de la Windows seule**. Les dossiers encadrés ci-dessous ne sont accessibles que par la machine avec Windows sur laquelle vous étiez au moment des modifications. *voir image ci-dessous*.

Pour éditer et retrouver des fichiers d'une session Windows à une autre, un lecteur réseau attaché peut être utilisé. Celui-ci pointe vers le serveur de stockage sur lequel votre session Debian récupère son `/home`. *voir image ci-dessous*

Grand raccourci : **sur Windows un disque réseau est attaché contenant les fichiers de votre session Debian; l'utiliser pour stocker et éditer des fichiers sur votre Windows et les stocker directement sur votre Debian me semble intéressant..**


## Accès à vos fichiers à distance

L'installation peut se faire manuellement vu ci-dessous ou par les scripts présents dans ce dépôt.

### Sur Windows
Téléchargez le fichier de configuration OpenVPN de l'IUT (https://vpn.univ-pau.fr/uppa_etudiant_v1.ovpn).

Téléchargez et installez le fichier d'installation en `.msi` de OpenVPN (https://openvpn.net/community-downloads/).

Lancez OpenVPN depuis votre Menu Démarrer, une icône sur le bureau, la barre de recherche.. Il apparait en bas à droite de votre barre des tâches, peut-être dans la zone de notification. *mettre image de moi windows openvpn dans barre des tâches*

*Clique droit -> Importer* avec votre fichier de configuration téléchargé puis *Connexion*. <br> Si réouverture : *Clique droit -> Connection*

mettre ajouter un lecteur réseau ici + explications


### Sur GNU/Linux (ex. Ubuntu)
