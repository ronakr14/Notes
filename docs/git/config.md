# Config Settings

**Repository level settings take priority over global settings.*

##  Global Settings

### Add Global Identity
```git config --global <section name> <details>```

### Remove Global Identity
```git config --global --remove-section <section name>```

### Force Git to skip global settings
```git config --global user.useConfigOnly true```

### Add Global username and useremail
```
git config --global user.name "Your Name"
git config --global user.email mail@example.com
```

### Set VSCode as Git Default editor
```git config --global core.editor "code --wait"```

### Set your file compatible for windows and linux.(for windows user)
```git config --global core.autocrlf true```
```git config --global core.autocrlf input```

## Repository Settings
These settings are applied to the git repository.

### Add Global Identity
```git config  <section name> <details>```

### Remove Global Identity
```git config  --remove-section <section name>```

### Add Repository username and useremail
```
git config user.name "Your Login At Work"
git config user.email mail_at_work@example.com
```

