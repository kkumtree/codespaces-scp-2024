```bash
pwd
# Confirm that we are in `/workspaces/codespaces-scp-2024`
hugo new site . --force
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml
hugo server
```
