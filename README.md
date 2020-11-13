# alloyproxy.org
An easy Alloy instance to deploy to Heroku, any online IDE, or hosting it yourself.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/titaniumnetwork-dev/alloyproxy.org)

<a href="https://repl.it/github/titaniumnetwork-dev/alloyproxy.org" title="Run on Repl.it"><img alt="Run on Repl.it" src="https://repl.it/badge/github/titaniumnetwork-dev/alloyproxy" width="140" height="30"><img></a>

# How to use:

1. `git clone https://github.com/titaniumnetwork-dev/alloyproxy.org.git`

2. cd `alloy-server`

3. `npm install`

4. `npm  start`

# Configurations

You can use the normal Alloy configurations but this also comes with additional configurations in `config.json`.

```
"prefix": "/get/", // Sets prefix of proxy.
"ssl": false, // Sets the SSL of the app.
"port": "8080", // Sets the port of the app.
"cookie_auth": "__alloy_client=human" // If you don't want web crawlers coming and flagging your instance, then its highly recommended you use this. If you don't want this then remove this.
```


