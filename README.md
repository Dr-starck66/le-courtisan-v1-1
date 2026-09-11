# Le Courtisan V1.1 — Web app

Prototype responsive autonome, sans compte ni backend.

## Inclus
- Générateur de phrases versaillaises
- 6 personnages
- Élégance / sarcasme / arrogance / romantisme
- « Humiliez avec élégance », « Plus royal », « Plus mordant »
- Mode Conversation
- La Cour : publication locale + votes ⚜
- Titres de noblesse calculés selon les votes
- Duels de Cour
- Carte sociale + partage natif Web Share API / copie
- Majordome multicanal avec profils de contacts
- SMS, WhatsApp, Instagram, Facebook prévus comme connecteurs
- TikTok et Snapchat affichés comme canaux à valider selon leurs capacités API
- Données de démo persistées dans `localStorage`

## Lancer
Ouvrez `index.html` dans un navigateur moderne.

## Pour passer en production
1. Ajouter un backend (Node/Express, FastAPI, etc.).
2. Remplacer `courtify()` par `POST /api/generate` utilisant un fournisseur IA côté serveur.
3. Ajouter une base de données pour comptes, conversations, publications, votes et profils.
4. Ajouter authentification et modération pour La Cour.
5. Connecter les messageries canal par canal via API officielles et webhooks.
6. Vérifier signatures de webhook, permissions, limites et politiques de chaque plateforme.
7. Conserver une validation humaine par défaut pour les messages sensibles.

## Sécurité
Ne jamais placer de clé API privée dans `app.js` ou dans le navigateur.
