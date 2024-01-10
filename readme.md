# Build Push Check action

- build image docker
- push sur repo custom
- test avec grype

## to release a new version

```bash
# si tu veux delete un tag distant
git tag -d v2
git push origin :refs/tags/v2

# procédure "standard"
git tag -a -m "..." v2
git push --follow-tags
```