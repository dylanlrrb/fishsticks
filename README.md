# Install packages

```console
bash install.sh

# (add aws credentials for programatic script access to AWS)

# (OPTIONAL) disable news on login: 
# 1. edit /etc/default/motd-news and change
# ENABLED=1 to ENABLED=0
# 2. edit /etc/update-motd.d/80-livepatch and add  
# exit 0
# after the "#!/bin/sh.
# 3. edit /etc/update-motd.d/10-help-text and remove the printf lines or put exit 0 before them.

```
