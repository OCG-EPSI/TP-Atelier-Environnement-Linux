# 🖥️ Atelier Environnement Linux

---

## 📌 Pré-requis
- Une machine **Debian** (13 recommandé)  
- Au moins un **client Windows ou Debian** avec interface graphique pour les tests  
- Connexion réseau entre serveur et client
---

## 🛠️ Étapes de l’atelier
### 1️⃣ Installation et configuration du **DNS**
- Installation et configuration de Bind avec zone direct et reverse
- Vérifier la résolution depuis un client

---

### 2️⃣ Installation et configuration du **DHCP**
- Installation et configuration du DHCP avec KEA ou ISC
- Vérifier l’attribution automatique d’IP sur un client

---

### 3️⃣ Mise en place d’un **Apache ou Nginx** avec **WordPress**
- Installer et configurer un serveur web avec Wordpress ET Glpi
- Vérifier leurs accessibilité

---

### 4️⃣ Installation et configuration de **proftpd**
- Pouvoir accéder depuis le client avec filezilla

---

### 5️⃣ Gestion d'un **full**
- Ajouter un nouveau disque de 1G avec LVM
- Remplissez le à l'aide de la commande dd
- Ajouter de nouveau un disque de 1G pour étendre le précédent afin de rajouter de la place

---

### 6️⃣ Mise en place d'un dossier partagé
- Mise en place d'un dossier /srv/projet
- Autoriser que le groupe "developpeur" à écrire dedans

---

### 7️⃣ Mise en place d'un filer avec NFS
- Le client doit pouvoir connecter son filer NFS directement

---
