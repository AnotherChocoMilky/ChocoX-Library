# Contributing to ChocoX

Hey! Thanks for wanting to contribute 🍫  
Whether you want to add new repos or help improve the project, this guide will help you get started.

---

## Adding a new repo

To add a repo to ChocoX:

1. Fork this repository  
2. Open `back/global-repos.json`  
3. Add a new entry like this:

```json
{
  "url": "https://example.com/repo.json"
}
```

4. Commit your changes  
5. Open a pull request  

### Tips

- Make sure your URL points to a valid JSON file with the expected structure
- Only submit repos you have the right to share
- Keep your PR description clear so it’s easy to review

---

## Commit messages

Keep commit messages simple and descriptive. Convention:

- **feat:** new feature (including adding a repo)
- **fix:** bug fix or typo fix
- **chore:** maintenance, formatting, small tweaks
- **docs:** documentation updates
- **refactor:** code cleanup without behavior changes

### Examples

```txt
feat: add example repo to global-repos.json
fix: correct URL for existing repo
docs: update contributing guide
chore: update badges
```

---

## Code style & guidelines

- Keep JSON valid and consistently formatted
- Respect the lightweight/minimal spirit of the project
- Don’t break the static site build or deployment (GitHub Pages/Vercel/etc.)

---

## Review process

- Maintainers will review your pull request
- If changes are requested, please update your PR
- Once approved, it will be merged into `main`

---

Thanks again for helping improve ChocoX! 🚀
