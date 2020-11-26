# xhub-signature

Utilitaire de signature de payload.  

Github signe ses webhooks avec l'algorithme 'sha256'.  

Pour pouvoir réaliser des tests ou déclencher un webhook manuellement, il est donc intéressant de pouvoir simuler ce mécanisme de signature, ce que propose xhub-signature, sous forme de GUI.

## Installation

```
npm install
```

## Compile avec hot-reloads pour le développement
```
npm run serve
```

### Compile et minifie pour la production
```
npm run build
```

### Linter
```
npm run lint
```

### Configurations Vue-CLI
Voir [la documentation](https://cli.vuejs.org/config/).
