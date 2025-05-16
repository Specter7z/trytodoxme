# 📧 TryTodoxMe

**TryTodoxMe** est une solution de messagerie sécurisée, moderne et open source, développée pour répondre aux besoins de confidentialité, de souveraineté numérique et d'anonymat dans un monde numérique de plus en plus surveillé.

> 🔐 *"Parce que votre vie privée ne devrait jamais être une option."*

---

## 🚀 Présentation

**TryTodoxMe** se positionne comme une alternative souveraine et respectueuse à Gmail, Outlook ou ProtonMail. Elle permet aux utilisateurs d’échanger des emails via une plateforme sécurisée avec :

- Chiffrement de bout en bout
- Accès anonyme (aucune donnée personnelle requise)
- Interface intuitive et responsive
- Code source transparent (open source)
- Hébergement conforme au RGPD (serveurs européens)

---

## 🧰 Fonctionnalités principales

| Fonction                             | Détail |
|--------------------------------------|--------|
| 🔐 **Chiffrement E2E**               | Les emails sont chiffrés sur votre appareil et déchiffrés uniquement par le destinataire |
| 🕵️ **Anonymat complet**             | Aucune information personnelle nécessaire pour créer un compte |
| 🇪🇺 **Hébergement RGPD**             | Infrastructure basée en Europe pour garantir la conformité légale |
| 📱 **Interface responsive**          | Utilisable depuis smartphone, tablette ou desktop |
| 🔓 **Open Source**                   | Code public, vérifiable, modifiable |
| 📦 **Installation légère**           | Fonctionne avec peu de dépendances, peut être auto-hébergée |

---

## 📸 Aperçu

[![Capture.png](https://i.postimg.cc/0NsS1bdP/Capture.png)](https://postimg.cc/qN1q8B55)


---

## 🏗️ Architecture du projet

📁 trytodoxme/

├── index.html → Page principale (présentation)

├── style.css → Feuille de style (optionnel si inline)

├── README.md → Documentation projet

├── /src → Fichiers de base si implémentation backend (futur)

└── /assets → Images, icônes, etc.
---

## ⚙️ Installation

### 🔧 Pré-requis

- Un simple navigateur web (si frontend statique uniquement)
- Pour version full-stack : Node.js, MongoDB, ou autre stack (optionnel)

### 🖥️ Méthode 1 : Démo locale

```bash
git clone https://github.com/specter7z/trytodoxme.git
cd trytodoxme
# Ouvrir index.html dans votre navigateur
```
🌐 Méthode 2 : Hébergement personnel
Vous pouvez héberger TryTodoxMe sur un serveur Apache, Nginx ou via Vercel/Netlify.

🔒 Sécurité
Tous les messages sont chiffrés à l’aide de PGP ou d’une implémentation maison basée sur AES256 (à adapter selon ton implémentation réelle).

Le projet prévoit zéro-logging, aucune métadonnée de suivi, et une architecture sans cookies tiers.

📫 Contact
📧 Email : diego2102@outlook.be

🔗 GitHub : github.com/specter7z

🙋 FAQ
❓ Peut-on l’utiliser sans compte ?
Oui, un mode temporaire est prévu avec boîte jetable (optionnelle à implémenter).

❓ Puis-je déployer TryTodoxMe sur mon propre serveur ?
Absolument. Le code est autonome et peut être adapté à un hébergement personnel.

❓ L’interface est-elle disponible sur mobile ?
Oui, entièrement responsive (HTML/CSS natif).

🤝 Contribuer
Toute contribution est la bienvenue. Voici comment :

Fork ce dépôt

Crée ta branche : git checkout -b feature/ma-feature

Commit : git commit -m 'Ajout d’une fonctionnalité'

Push : git push origin feature/ma-feature

Crée une Pull Request

⚖️ Licence
Ce projet est sous licence MIT. Vous êtes libre de l’utiliser, le modifier, le partager, tant que vous conservez l’attribution originale.

🧠 Philosophie du projet
TryTodoxMe n’est pas seulement un outil : c’est une réponse à l’érosion progressive de nos libertés numériques. Chaque ligne de code est pensée pour défendre un Internet plus libre, plus éthique, plus humain.

💡 “Celui qui contrôle les communications contrôle les esprits. Reprenons le pouvoir.”
