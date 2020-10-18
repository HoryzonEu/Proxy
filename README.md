# Horyzon Proxy

Bienvenue sur le serveur Proxy du projet Horyzon.

## Contribution
Vos contributions sont les bienvenues et doivent être approuvées par un administrateur. Si celle-ci est validée, elle est alors fusionné au projet et effective sur le serveur lors de son redémarrage quotidien.

## Obfuscation
Certaines données sont sensibles et ont donc été soit supprimé (plugins payants), soit obfusqué (identifiants BDD, Token).
Cependant tous les fichiers de configuration restent disponible à la modification et les variables obfusquées sont désobfusquées sur notre serveur en sécurité.

## Variables

### Propriétés serveur
Pour les propriétés serveur, veuillez utiliser les variables suivantes :
```bash
Public address: '$public_address'
Local address: '$local_address'

Proxy port: '$proxy_port'
Proxy query: '$proxy_query'

Hub server port: '$server_hub_port'
Auth server port: '$server_auth_port'
Survie server port: '$server_survie_port'
Creatif server port: '$server_creatif_port'
Event server port: '$server_event_port'
Archi server port: '$server_archi_port'
Dev server port: '$server_dev_port'
```

### Votifier
Pour les informations de connexion avec Votifier :
```bash
Port: '$votifier_port'
Token: '$votifier_token'
Private key: '$votifier_key_private'
Public key: '$votifier_key_public'
```

### Base de donnée
Il est préférable de favoriser l'utilisation de MySQL ou MariaDB lorsqu'il l'est possible.
Pour les informations de connexion, veuillez utiliser les variables suivantes :
```bash
Host: '$mysql_host'
Port: '$mysql_port'
```

Pour les identifiants de connexion pour les données communes à différents serveurs, veuillez utiliser les variables suivantes :
```bash
User: '$mysql_user_proxy'
Password: '$mysql_password_proxy'
Database: '$mysql_database_proxy'
```

### Bot Discord
Pour les identifiants du Bot Discord BreakerBot, veuillez utiliser les variables suivantes :
```bash
Invite: '$discord_invite'
```

### AntiVPN
Les tokens de services anti-vpn :
```bash
IpHub: '$antivpn_iphub'
ProxyCheck: '$antivpn_proxycheck'
```