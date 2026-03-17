# Audit Ports SavQonnect — Page IT

Page web statique dérivée de `docs/AUDIT_PORTS_RELATIONS_SAVQONNECT.md`, destinée aux équipes TI pour l'application des règles ACL (firewall).

## Contenu

- **Règles ACL** : Blocs prêts à copier (entrant, sortant cloud, sortant VLAN AV, infrastructure)
- **Ports entrants/sortants** : Tableaux de référence
- **Services cloud** : Domaines HTTPS à autoriser
- **Infrastructure interne** : Connexions vers Mac Mini, Oracle, DDM

## Utilisation

1. Ouvrir `index.html` dans un navigateur (ou héberger sur un serveur interne)
2. Remplacer `VM_IP` par l'adresse IP de la VM SavQonnect dans les règles
3. Utiliser les boutons **Copier** pour exporter les blocs vers la config firewall

## Design

- Thème sombre (confort pour environnements IT)
- Typographie IBM Plex
- Compatible impression (les boutons sont masqués à l'impression)
- Autonome (un seul fichier HTML avec CSS/JS inline)

## Source

`../../docs/AUDIT_PORTS_RELATIONS_SAVQONNECT.md`
