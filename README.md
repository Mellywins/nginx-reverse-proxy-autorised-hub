# Introduction
This project is meant to automatize the creation and renewal of SSL certificates on an nginx reverse proxy. You can maintain the SSL certifacte on the proxy instead of having them on each proxied server.
This project uses CertBot issed certificates and makes use of its auto renewal.
Note that you have to have a *WORKING* DNS associated to your server IP and make sure that you have PORT 80 and 443 enabled via your firewall so that Certbot can download meta files for its configuration.
## Mentions
Special thanks to [Jonas Alfredson](https://github.com/JonasAlfredsson) For his amazing image