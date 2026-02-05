# Workflow & gouvernance éditoriale

## Cycle de vie des articles
1. **Draft** : article en cours de recherche et de rédaction.
2. **Published** : article validé et prêt à diffusion.
3. **Archived** : contenu obsolète ou remplacé par une version mise à jour.

Les fichiers doivent être déplacés dans :
- `/articles/drafts`
- `/articles/published`
- `/articles/archived`

## Proposer un article (Issues GitHub)
- Utiliser le modèle **Article Proposal**.
- Définir la question centrale, le périmètre, et les sources pressenties.
- Ajouter les labels :
  - `draft` (proposition en cours)
  - `needs data` (données manquantes)
  - `validated` (prêt à publier)
  - `outdated` (à archiver)

## Revue et validation (Pull Request)
- Chaque article passe par une **PR**.
- La PR doit inclure :
  - La checklist de validation complétée.
  - Les sources citées.
  - La section “Ce que cela change”.

## Critères avant publication
- Minimum **2 sources** traçables.
- Respect du ton et de la logique éditoriale.
- Conclusions actionnables.
- Périmètre explicitement défini.

## Versioning
- Une mise à jour substantielle crée une **nouvelle version** en draft.
- L’ancienne version passe en archived avec une note d’archivage.
