# oauth-dev-tool
This is a tool for OAuth 2.0 development

## Installation
```
curl -s https://api.github.com/repos/masa0221/oauth2-dev-tool/releases/latest | jq -r '.assets[0].browser_download_url' | xargs curl -L -O
```

```
chmod +x ./oauth && mv ./oauth /usr/local/bin/
```

