# Pourquoi ce document ?

Pour simplifier l'accès aux fichiers des machines physiques sous Windows et Debian :  je fais ce document pour avoir accès à leurs fichiers sous vos machines Windows et Linux n'importe où sur un poste de l'IUT ou chez vous.

Plus besoin de clé USB pour transférer des fichiers entre vos machines physiques sous Windows et Debian; non plus pour amener vos fichiers pour travailler chez vous après explications.

A l'issue de ce documents si vous le souhaitez, vos fichiers seront accessibles sur toutes vos machines à l'IUT sous Windows ou Debian et chez vous.

## Rappel sur le stockage des machines physiques
Les machines physiques sont montées avec un dual-boot Debian/Windows en réseau. 

Les sessions Debian sont synchronisées entre les machines physiques via leur `/home`. *Si vous ouvrez une session Debian sur une machine physique et que vous téléchargez ou éditez des fichiers : ces changements seront accessibles sur n'importe quelle session Debian à l'IUT avec vos identifiants.*

**Les sessions Windows ne sont pas synchronisées entre les machines physiques les modifications seront appliquées sur la machine physique seule**. Je vous recommande franchement de ne pas utiliser les répertoires initiaux de Windows (Téléchargements, Documents, Vidéos...) *voir image ci-dessous*.

Pour éditer et retrouver vos fichiers d'une session Windows sur d'autres machines physiques Windows, un lecteur réseau est attaché au démarrage sur les sessions Windows. Celui-ci pointe vers le serveur de stockage sur lequel votre session Debian récupère son `/home`. *voir image ci-dessous*

Pour faire un grand raccourci : **sur Windows vous avez un disque réseau attaché contenant les fichiers de votre session Debian; vous pouvez l'utiliser pour stocker et éditer vos fichiers quand vous serez aussi sur Windows. Vous aurez donc accès à vos fichiers sur vos machines Debian et Windows sur n'importe quelle machine physique peu importe son OS**. *(ça peut aussi permettre de transférer ses fichiers super facilement vos sessions Windows à Debian, sans clé USB)*


## Accès à vos fichiers à distance


### Utilisation du VPN de l'IUT
#### Sur Windows
#### Sur GNU/Linux (ex. Ubuntu)

### Accès au serveur de fichiers
#### Sur Windows
#### Sur GNU/Linux (ex. Ubuntu)
a
