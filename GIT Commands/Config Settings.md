# Config Settings

**Repository level settings take priority over global settings.*

##  Global Settings

Syntax: 
```git config --global <section name> <details>```

Examples:
```
git config --global user.name "Your Name"
git config --global user.email mail@example.com
```

## Remove Global Identity

Syntax:
```git config --global --remove-section <section name>```

Examples:
```
git config --global --remove-section user.name
git config --global --remove-section user.email
```

## Force Git to skip global settings
Command:
```git config --global user.useConfigOnly true```

## Repository Settings
Following command should be executed in repository itself.

Syntax:
```git config <section name> <details>```

Examples:
```
git config user.name "Your Login At Work"
git config user.email mail_at_work@example.com
```

