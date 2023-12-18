# Flapi_WebSite_BackEnd

TODO - TECH STACK :
- CI / CD (Github actions)
- Docker Compose v3.8 (Mode development)
- Dockerfile (Production) -> deploy in DockerHub
- Kubernetes (Create manifest files)
- Nuxt v3
- Tauri core v1.5.2, api v1.5.1, cli v1.5.5
- AdonisJS v5
- Ionic v7
- Capacitor v6
- Vitest v1
- Vitepress >= v1.0.0-rc.32
- Husky, prettier, eslint
- TailwindCSS >= 3.3.6
- Bucket S3 (via Minio)
- Mailhog
- PhpMyAdmin
- MariaDB
- MinioMC

<br /><br /><br />

Docker Compose inclus :
- Minio
- MinioMC
- MariaDB
- Mailhog (email)
- PhpMyAdmin

<br /><br /><br />

# Caractéristiques Principales
## Site Web Vitrine
- Inspiré de [Strapi](https://strapi.io/)
- Présente les fonctionnalités et avantages de FlapiCMS.

## Documentation du Site
- S'inspire de la documentation de [Strapi](https://docs.strapi.io/dev-docs/intro).
- Guide détaillé pour les utilisateurs et développeurs.

## Dashboard Administrateur
- Gestion du système de paiement via Stripe.
- Système de support client intégré.
- Gestion du contenu de la documentation, y compris les sections et sous-sections.
- Gestion de devis et factures.

## Déploiement et Production
- Utilisation de GitHub Actions pour l'intégration et la livraison continues.
- Mise en œuvre de Kubernetes pour la gestion et l'orchestration des conteneurs.
- Utilisation de Docker Compose pour le development de l'application.
- Création de Dockerfile pour la production puis déploiement vers Docker Hub puis utilisation de Kubernetes à partir des images Docker du Docker Hub.

## Développement
### Frontend
- Utilisation de NuxtJS 3.
- Tests unitaires avec Vitest.
- Configuration initiale avec linters, Prettier, ESLint.
- Scripts de pré-commit pour la vérification du code (Husky).

### Backend
- Basé sur AdonisJS.
- Suivi des meilleures pratiques de codage propre et maintenable.
