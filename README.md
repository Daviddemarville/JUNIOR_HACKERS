# 👾 Junior Hackers

Un mini-site interactif React destiné à faire découvrir la programmation, les mécaniques de jeu et l'envoi de messages à travers un parcours ludique et pédagogique.

----------------------------------------------------------------------------------------------------

🎉 Projet développé dans le cadre de la formation de développement web fullStack.
Wild Code School Session Mars 2025

Equipe :

- Bamba
- David
- Eulalie
- Thibaud

----------------------------------------------------------------------------------------------------

## 🚀 Fonctions principales

- 🎲 **Jeu de l'oie en React** : un plateau interactif avec avatars, questions par cases, et système de progression pour 1 ou 2 joueurs.
- 📩 **Formulaire de contact connecté à EmailJS** : permet d’envoyer un message via e-mail sans backend.
- 🧠 **Gestion des erreurs et des réponses** : déplacement des pions basé sur la logique bonne/mauvaise réponse.
- 💾 **Persistances des positions** : les positions des pions sont sauvegardées dans `localStorage`.

----------------------------------------------------------------------------------------------------

## 🛠️ Stack technique

- **React 18**
- **Vite**
- **TypeScript**
- **Tailwind CSS**
- **EmailJS** (pour l’envoi de messages)

----------------------------------------------------------------------------------------------------

## 📁 Structure rapide

src/
├── components/ # Pions, plateau, question bubble...
├── pages/ # Page principale et formulaire de contact
├── assets/ # Images du jeu (Algobot, pions, etc.)
├── styles/ # Fichiers Tailwind ou CSS

----------------------------------------------------------------------------------------------------

## ⚙️ Installation & lancement

1. Clone le repo
2. Installe les dépendances :

```bash
npm install
npm run dev

----------------------------------------------------------------------------------------------------

✉️ Configuration EmailJS
Pour que le formulaire fonctionne :

Crée un compte sur https://emailjs.com

Crée un service, un template et récupère :

Service ID

Template ID

Public Key

Remplis ces infos dans Contact.tsx

----------------------------------------------------------------------------------------------------

📄 Licence
Ce projet est mis à disposition selon les termes de la licence Creative Commons BY-NC 4.0.

🛑 Utilisation non commerciale uniquement.
📚 Attribution obligatoire.
🔧 Aucune redistribution commerciale autorisée sans consentement préalable.

----------------------------------------------------------------------------------------------------