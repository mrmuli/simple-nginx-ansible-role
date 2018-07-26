# simple-nginx-ansible-role

A simple role for installing Nginx and cofiguring a few proxy settings
1. CORS
2. Upstream and Downstream Encryption
3. Upstream config for http and tcp connections
4. HTTPS redirects #TODO
5. Passive healthchecks (active only works with NGINX Plus)


The default algorithm used is round robin, opt on changing this to least conn or adding upstream weight if you prefer that. Check out the available vars