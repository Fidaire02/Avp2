# Guide de contribution

Merci de contribuer au projet **Pipeline_CI** 🎉

## Workflow Git
- Les contributions se font via des **branches de fonctionnalité** (`feature/...`).
- Les branches doivent être fusionnées dans `develop` via une **Pull Request**.
- La branche `main` est protégée et ne reçoit que du code validé.

## Convention de commits
Nous utilisons la norme **Conventional Commits**.

Format :
`<type>(scope): <description>`

Types autorisés :
- feat : ajout d’une fonctionnalité
- fix : correction de bug
- docs : documentation
- style : formatage du code
- refactor : amélioration du code
- test : ajout ou modification de tests
- chore : tâches diverses

Exemples :
- `feat(api): ajout d’un endpoint`
- `fix(ci): correction du pipeline`
- `docs(readme): mise à jour du README`

## Pull Requests
- Toute modification doit passer par une **Pull Request**.
- La Pull Request doit être validée par au moins un membre.
- Le pipeline CI doit être **vert** avant la fusion.
- Les discussions doivent être résolues avant le merge.

## Bonnes pratiques
- Ajouter des tests pour toute nouvelle fonctionnalité.
- Respecter la structure du projet.
- Maintenir un code lisible et documenté.
