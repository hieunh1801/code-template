# Git credential

```bash
# enable cache
git config --global credential.helper cache

# set timeout for cache
git config --global credential.helper 'cache --timeout=999999999'

# disable cache
git config --global --unset credential.helper
```