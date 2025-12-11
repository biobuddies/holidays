# Python Django Project Bootstrap - Completed Steps

## 1. Package Name Availability Check

```bash
pip search package-name
```

## 2. Bootstrap with Helicopyter Cookiecutter

Set up tool versions and run cookiecutter template:

```bash
asdf plugin add nodejs
asdf install nodejs latest
asdf set nodejs latest
asdf plugin add uv
asdf install uv latest
asdf set uv latest
uvx cookiecutter https://github.com/biobuddies/helicopyter/archive/refs/heads/main.zip --no-input --overwrite-if-exists
```
