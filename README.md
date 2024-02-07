# cncrp
Cloudflare Nginx Certbot Reverse Proxy

This role sets up an Nginx server, and configures it as a reverse proxy, with HTTPS certificate from certbot using DNS-01 challenge through Cloudflare. Also this role automatically sets up auto-renewals. See `example-playbook.yml` for usage.