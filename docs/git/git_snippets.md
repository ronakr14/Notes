# Git Snippets

## Multiple Git Repositories Download
```GHUSER=ronakr14; curl "https://api.github.com/users/$GHUSER/repos?per_page=1000" | grep -w clone_url | grep -o '[^"]\+://.\+.git' | xargs -L1 git clone```

** change GHUSER to user from where you want to download the repositories.