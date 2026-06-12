# Methodamin

Plateforme de création et gestion d'entreprises en ligne.

## Pages

| Page | Description |
|------|-------------|
| `index.html` | Page d'accueil + formulaire rapide |
| `creation-entreprise.html` | Stepper 6 étapes — création d'entreprise |
| `login-client.html` | Connexion / Inscription (Supabase Auth) |
| `espace-client.html` | Portail client — dossiers, messagerie, documents |
| `espace-admin.html` | Dashboard admin — KPIs, dossiers, devis |
| `services.html` | Présentation des services |
| `faq.html` | Questions fréquentes |
| `contact.html` | Formulaire de contact |
| `reset-password.html` | Réinitialisation mot de passe |
| `mentions-legales.html` | Mentions légales |
| `confidentialite.html` | Politique de confidentialité |

## Stack

- **Frontend** : HTML / CSS / JS vanilla
- **Backend** : Supabase (BDD PostgreSQL + Auth + Storage)
- **Hébergement** : Vercel

## Déploiement

1. Connecter ce repo sur [vercel.com](https://vercel.com)
2. Déploiement automatique à chaque push sur `main`
3. Créer le bucket Storage `demarches-documents` dans Supabase Dashboard

## Supabase

- Project ID : `sahbhyccnkcqjzxkyzol`
- Région : eu-west-2 (Europe)
