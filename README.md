# GAM (for Google Workspace) Documentation - Sphinx Material-Themed

<!-- 
[![Uptime](https://status.oxl.at/api/v1/endpoints/1--oxl_documentation/uptimes/7d/badge.svg)](https://status.oxl.at/endpoints/1--oxl_documentation)
-->

EN 🇬🇧: [gam.docs.oxl.app](https://gam.docs.oxl.app)

[![Docs Uptime](https://status.oxl.at/api/v1/endpoints/4--docs-mirrors_docs-mirror-gam-for-google-workspace/uptimes/7d/badge.svg)](https://status.oxl.at/endpoints/4--docs-mirrors_docs-mirror-gam-for-google-workspace)

This is a mirror of the [official GAM documentation](https://github.com/GAM-team/GAM/wiki) so it easier accessible for new users.

## Build

Run:

```
apt install git python3-pip

# with VENV
apt install python3-virtualenv 
bash venv.sh

# WITHOUT
pip install -r requirements.txt

# USAGE: bash html.sh <BUILD-DIR> <DOMAIN> 
bash html.sh ./build/ gam.docs.oxl.app
```
