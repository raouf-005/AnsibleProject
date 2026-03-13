# Projet M1 SR — ADMINSYSRES2 2026

## Structure du projet

```
projet-m1-adminsysres2/
├── ansible/
│   ├── inventories/hosts.ini      # Inventaire des machines
│   ├── group_vars/                # Variables par groupe
│   ├── ansible.cfg                # Configuration Ansible
│   ├── 01-nfs-partage.yml         # Partie 1 :
│   ├── 02-stp-redondance.yml      # Partie 2 :
│   ├── 02-rstp-redondance.yml     # Partie 2 :
│   ├── 03-tolerance-access.yml    # Partie 3 :
│   ├── 04-redondance-routeur.yml  # Partie 4 : VRRP
│   └── roles/                     # Rôles Ansible réutilisables

```

## Prérequis

- VMware Workstation/Player
- VMs : Debian/CentOS (sans GUI, 1 CPU, 500MB RAM)
- VMs Cumulus Linux (1 CPU, 650-700MB RAM)
- Ansible installé sur la machine de contrôle
- Interfaces réseau en mode "LAN Segment"

## Membres du groupe

- Étudiant 1 : Derardja Abderraouf
- Étudiant 2 : Ayoub bouaya
