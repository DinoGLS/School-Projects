# Reseaux Double Vlan Simple

Je joint un fichier pkt du nom de projet debutant que j'alimenterais avec différentes modifications et explications.

Voici une configuration d'un réseau Vlan simple avec double Vlan, un router et un server dhcp attribuant des adresses aux appareils des deux Vlan.

~~~diff
+ VLAN Accueil : 192.168.2.1/150 (Actif)
+ VLAN Gestion : 192.168.3.1/150 (Actif)
+ Server DHCP (Actif)
+ Point d'Acces Wireless WIFI (Actif) WIFI2 (Actif)
~~~~