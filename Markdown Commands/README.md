# Notes

## download_multipe_git_repos
Command to download multiple repositories from github:
<br>
  GHUSER=ronakr14; curl "https://api.github.com/users/$GHUSER/repos?per_page=1000" | grep -w clone_url | grep -o '[^"]\+://.\+.git' | xargs -L1 git clone
