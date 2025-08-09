# Guide de contribution

Ce document explique comment contribuer au projet et quelles conventions suivre.

## 📜 Convention de nommage des commits (Conventional Commits)

Chaque message de commit doit commencer par un **type** suivi de `:` et d’une brève description.

### Types courants
- **feat:** nouvelle fonctionnalité
- **fix:** correction d’un bug
- **docs:** mise à jour de la documentation
- **style:** changements de style (indentation, formatage…)
- **refactor:** amélioration du code sans changement de fonctionnalité
- **perf:** optimisation des performances
- **test:** ajout ou modification de tests
- **build:** modification du build ou des dépendances
- **ci:** changements liés à l’intégration continue
- **chore:** maintenance mineure, nettoyage

### Exemples
```
feat: ajout du formulaire de contact
fix: correction de l’affichage sur mobile
docs: mise à jour du README
```

## 🔄 Workflow Git

1. **Créer une branche** pour chaque nouvelle fonctionnalité ou correction :
```bash
git checkout -b feat/nom-fonctionnalite
```

2. **Commiter régulièrement** en suivant la convention ci-dessus.

3. **Pousser** la branche sur GitHub :
```bash
git push origin feat/nom-fonctionnalite
```

4. **Créer une Pull Request** depuis GitHub pour demander la fusion dans `main`.

---

## 🗂 Correspondance Labels ↔ Types de commits

| Label GitHub | Type de commit associé | Exemple de message de commit |
|--------------|------------------------|------------------------------|
| **bug** | `fix:` | `fix: correct form validation error` |
| **feature** | `feat:` | `feat: add candidate search filter` |
| **documentation** | `docs:` | `docs: update installation guide` |
| **enhancement** | `refactor:` ou `feat:` selon le cas | `refactor: improve dashboard layout` |
| **priority: high** | dépend du type réel | `fix: resolve critical login bug` |
| **priority: medium** | dépend du type réel | `feat: add pagination to results` |
| **priority: low** | dépend du type réel | `chore: update footer links` |
| **design** | `style:` ou `feat:` | `style: improve button hover effect` |
| **discussion** | pas de commit direct (sert à l’échange) | — |
| **security** | `fix:` ou `chore:` selon le cas | `fix: patch SQL injection vulnerability` |
| **good first issue** | dépend du type réel | `docs: add basic contribution guide` |
| **status: to do** | — (suivi projet, pas commit) | — |
| **status: in progress** | — (suivi projet, pas commit) | — |
| **status: done** | — (suivi projet, pas commit) | — |
| **question** | pas de commit direct (sert à clarifier) | — |
| **help wanted** | pas de commit direct (sert à demander aide) | — |
| **build** | `build:` | `build: update npm dependencies` |
| **chore** | `chore:` | `chore: clean up unused imports` |
