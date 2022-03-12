# oauth-dev-tool
This is a tool for OAuth 2.0 development

## Installation
### Homebrew
```
brew tap masa0221/tap && brew install oauth2-dev-tool
```


### Manual install
```sh
curl https://raw.githubusercontent.com/masa0221/oauth2-dev-tool/HEAD/oauth -o /usr/local/bin/oauth && chmod +x /usr/local/bin/oauth
```

## Usage 

```
oauth is a tool for OAuth 2.0 development

Usage:
    oauth client create [NAME]  Create client config file
    oauth client list           Display list of clients
    oauth client show NAME      Show config of specified client
    oauth client delete NAME    Delete config of specified client
    oauth new [NAME]            Alias command of client new
    oauth auth                  Open authorize and authentication URL
    oauth token CODE|refresh    Issue token or Reissue token
                                The subcommand reflesh can be get new token using by reflesh token when already issue token.

Options:
    -n                   Specifiy client config file name
    -h                   print this
```
