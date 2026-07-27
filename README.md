<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7b2cbf,100:c77dff&height=200&section=header&text=AzureLab%20Dashboard&fontSize=50&fontAlignY=40&animation=twinkling&desc=Monitoring%20%26%20Gestion%20Infrastructure%20Cloud%20Azure&descAlignY=60&descAlign=50" alt="AzureLab Dashboard Banner" />

  <p align="center">
    <img src="https://img.shields.io/badge/Language-PHP_8.x-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
    <img src="https://img.shields.io/badge/Cloud-Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure">
    <img src="https://img.shields.io/badge/Frontend-Bootstrap_%2F_CSS3-563D7C?style=for-the-badge" alt="Frontend">
    <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License">
  </p>

  <p align="center">
    <b>Un tableau de bord web interactif en PHP pour superviser, démarrer et administrer rapidement vos ressources Azure Lab.</b>
  </p>
</div>

---

## 📖 Présentation

**AzureLab Dashboard** est une solution web légère développée en PHP permettant de visualiser l'état de votre infrastructure Cloud Azure Lab en un coup d'œil. Elle offre un suivi en temps réel de vos machines virtuelles (VMs), de leur état d'exécution (Running / Stopped), de l'utilisation des ressources et des coûts associés.

---

## ✨ Fonctionnalités

- 📊 **Vue d'Ensemble des Ressources :** Liste de l'ensemble des VMs, groupes de ressources et réseaux virtuels (VNet).
- ⚡ **Contrôle Énergie :** Boutons d'action pour démarrer, éteindre ou redémarrer les machines virtuelles directement depuis l'interface web.
- 📈 **Indicateurs de Santé :** Graphiques et métriques simples sur la consommation CPU et mémoire.
- 🔒 **Authentification Sécurisée :** Intégration avec les identifiants de Service Principal Microsoft Azure (Tenant ID, Client ID, Secret).

---

## 🛠️ Installation & Déploiement

1. Clonez ce dépôt sur votre serveur web (Apache / NGINX avec PHP 8.x) :
   ```bash
   git clone https://github.com/nexos20lv/AzureLab-Dashboard.git
   ```
2. Configurez vos identifiants Azure API dans le fichier de configuration `config.php` :
   ```php
   define('AZURE_TENANT_ID', 'votre-tenant-id');
   define('AZURE_CLIENT_ID', 'votre-client-id');
   define('AZURE_CLIENT_SECRET', 'votre-client-secret');
   define('AZURE_SUBSCRIPTION_ID', 'votre-subscription-id');
   ```
3. Ouvrez l'application dans votre navigateur et administrez votre lab Azure !

---

## 📄 Licence

Ce projet est sous licence **MIT**. Voir le fichier [LICENSE](LICENSE) pour plus de détails.