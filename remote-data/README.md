# Clubico — Remote Data

Package de données publiques pour le repo `shinzarou-eng/Clubico`.

## Structure

```
remote-data/
├── manifest.json          # Point d'entrée : baseUrl et fichiers
├── clubs.json             # Clubs de Ligue 1
├── players.json           # Joueurs (vide pour l'instant, à remplir)
├── agents.json            # Agents extraits
├── logos/
│   ├── manifest.json      # Index des logos
│   └── {slug}.png         # Logos clubs
└── agents/
    └── {id}.jpg           # Photos agents
```

## Commandes Git pour publier

```bash
git init
git remote add origin https://github.com/shinzarou-eng/Clubico.git
git add .
git commit -m "Initial data"
git push -u origin main
```

> Ne pas oublier de remplacer `main` par la branche cible si nécessaire.
