# Dérives

Projet d'application poétique réalisée à l'UTC au printemps 2021.
Site web de présentation : https://derives.utc.fr/

### [Tester l'application](Tester.md)

### Mettre à jour

Pour mettre à jour l'application :
- Faire ses commits sur une branche séparée puis la merge dans `develop`
- Bump la version avec `standard-version` en suivant les conventions semver : 
  ```bash
  npx standard-version --release-as patch
  ```
- Build l'application (`expo build`) puis la soumettre aux stores

Voir aussi :
- [Règles sonores](Règles%20son.md)
