# boilerplate

<!-- La description du projet doit être rédigée manuellement. -->

---

## Technologies

| Domaine | Technologies |
|---------|--------------|
| Frontend | Vite |
| Tests | Playwright (@playwright/test) |

---

## Prérequis

Les outils suivants sont nécessaires à l'installation et à l’exécution du projet.

| Outil | Version |
|--------|---------|
| Node.js | – |
| npm | – |

---

## Installation

### Clonage du dépôt distant

```bash
git clone https://github.com/floriansalvi/TB_Boilerplate
cd TB_Boilerplate
```

### Configuration

Copier le fichier d’exemple des variables d’environnement afin de pouvoir exécuter les scripts et l’application en local.

```bash
cp .env.example .env
```

### Installation des dépendances

#### Frontend

Installer les dépendances Node.js du projet.

```bash
npm install
```

### Démarrage

Démarrer le serveur de développement.

```bash
npm run dev
```

---

## Variables d’environnement requises

Les variables d’environnement suivantes doivent être adaptées avant l'exécution du projet.

| Variable | Description |
|-----------|-------------|
| APP_NAME | Nom de l’application. |
| APP_TIMEZONE | Fuseau horaire de l’application. |
| APP_URL | URL de base de l’application. |
| APP_LOCALE | Langue/locale par défaut. |
| APP_FALLBACK_LOCALE | Langue/locale de repli. |
| VITE_APP_URL | URL de l’application exposée au frontend (Vite). |
| VITE_API_URL | URL de l’API consommée par le frontend (Vite). |
| DB_CONNECTION | Pilote/type de base de données (ex. mysql, pgsql, sqlite). |
| DB_HOST | Hôte de la base de données. |
| DB_PORT | Port de la base de données. |
| DB_DATABASE | Nom de la base de données. |
| DB_USERNAME | Utilisateur de la base de données. |
| DB_PASSWORD | Mot de passe de la base de données. |
| DEFAULT_USER_NAME | Nom du compte utilisateur par défaut. |
| DEFAULT_USER_EMAIL | Email du compte utilisateur par défaut. |
| DEFAULT_USER_PASSWORD | Mot de passe du compte utilisateur par défaut. |
| DEFAULT_ADMIN_NAME | Nom du compte administrateur par défaut. |
| DEFAULT_ADMIN_EMAIL | Email du compte administrateur par défaut. |
| DEFAULT_ADMIN_PASSWORD | Mot de passe du compte administrateur par défaut. |

---

## Tests

### Exécution

Exécuter les tests end-to-end (Playwright).

```bash
npx playwright test
```

---

## Commandes utiles

| Commande | Description |
|----------|-------------|
| `npm run dev` | Démarre le serveur de développement (Vite). |
| `npm run build` | Génère une build de production (Vite). |
| `npm run readme:analyze` | Analyse le projet pour la génération de documentation (script interne). |
| `npm run readme:generate` | Génère le README à partir de l’analyse (script interne). |
| `npm run docs:readme` | Lance l’analyse puis la génération du README. |

---

## Documentation complémentaire

<!-- La documentation supplémentaire du projet doit être indiquée manuellement. -->
