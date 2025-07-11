# 🔐 Projet 07 – Tutoriel : SSH + WinSCP

## 🎯 Objectif
Expliquer comment :
- Installer OpenSSH Server sur Ubuntu
- Installer WinSCP sur Windows
- Transférer des fichiers entre les deux machines

---

## 🐧 1. Installer OpenSSH sur Ubuntu

```bash
sudo apt update
sudo apt install openssh-server
sudo systemctl status ssh
---
##  2. Installer WinSCP sur Windows
Télécharger : https://winscp.net
Installer en mode classique
Configuration :
Hôte : IP Ubuntu
Utilisateur : nom Linux
Protocole : SCP ou SFTP

Réalisé par : Thiané BOYE – Licence 2 Informatique – ESTM