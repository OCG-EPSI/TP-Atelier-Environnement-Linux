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

### 5️⃣ Gestion d'un full**
- Ajouter un nouveau disque de 1G avec LVM
- Remplissez le à l'aide de la commande dd
- Ajouter de nouveau un disque de 1G pour étendre le précédent afin de rajouter de la place

---

### 6️⃣ Création d’une **GPO pour bloquer l’accès au terminal**
- Configurer la stratégie pour interdire `cmd.exe`
- Tester depuis un compte utilisateur

---

### 7️⃣ Création d’un **partage de fichiers**
- Créer un dossier partagé avec droits NTFS
- Tester l’accès depuis un client du domaine

---

### 8️⃣ GPO pour **monter automatiquement le partage de fichiers**
- Créer une GPO de mappage de lecteur réseau
- Vérifier que le lecteur apparaît au login utilisateur

---

### 9️⃣ Mise en place d’un **profil itinérant**
- Activer les profils itinérants pour certains utilisateurs
- Tester la persistance des données après reconnexion sur un autre poste

---

### 🔟 Configuration d’un **contrôleur de domaine secondaire** (AD secondaire)
- Installer un deuxième serveur Windows
- Promouvoir en **contrôleur de domaine secondaire** pour la redondance
- Vérifier la réplication AD/DNS

---


### TODO

- Réfléchir à une hiérarchie des utilisateurs pour une entreprise avec un contexte
- Script powershell pour importer des utilisateurs depuis un fichier excel 