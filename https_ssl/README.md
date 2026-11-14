# alu-webstack

## https_ssl

| File | Description |
|------|-------------|
| `0-world_wide_web` | Bash script that shows the record type and destination of a domain's subdomains (www, lb-01, web-01, web-02) |
| `1-haproxy_ssl_termination` | HAproxy config on lb-01 that terminates SSL on port 443 for www.favournziza.tech |
| `2-redirect_http_to_https` | HAproxy config that also redirects all HTTP traffic to HTTPS with a 301 |
