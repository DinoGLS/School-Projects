# Recommandations et évolutions possibles


## I Sécurité


- Mettre en place des ACL pour filtrer les flux (ex : limiter l’accès TFTP/SNMP aux seules IP d’admin).
  
- Utiliser SNMPv3 (authentification, chiffrement) plutôt que SNMPv2c si possible.
​

## II Haute disponibilité avancée

- Ajouter des protocoles de redondance comme VRRP/GLBP pour les passerelles par défaut sur les LAN.
  
-  Tester des mécanismes de bascule WAN (IP SLA + tracking) pour garantir un accès entre les sites en cas de panne d’un lien.
​
​

## Supervision et logs

- Intégrer un serveur Syslog centralisé pour les logs des routeurs/switches en plus de SNMP.
  
- Ajouter des tableaux de bord (Grafana, LibreNMS, etc.) pour visualiser l’état du réseau.
​

## Évolution vers un environnement réel/entreprise

- Mettre en place un pare-feu entre LAN et WAN/Internet (zone DMZ pour les serveurs HTTP/DNS publics).
​