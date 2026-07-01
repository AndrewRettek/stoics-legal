# Stoics Legal

GitHub Pages source for Stoics legal documents.

Expected published URLs:

- `https://andrewrettek.github.io/stoics-legal/privacy/`
- `https://andrewrettek.github.io/stoics-legal/terms/`

Publish after attorney review:

```bash
gh repo create stoics-legal --public --source . --remote origin --push
gh api \
  --method POST \
  -H "Accept: application/vnd.github+json" \
  /repos/AndrewRettek/stoics-legal/pages \
  -f source='{"branch":"main","path":"/"}'
```
