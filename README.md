# docker-nginx-mikrus

This is a simple project to show how to easily launch a static website in nginx using your own domain name and proxy pass.

### Description and how to use?

Simply type `docker-compose up` and enjoy.

### What do you need?

* docker
* docker-compose
* your website is in `app` directory
* you setup Docker correctly to listen on IPv6 `https://docs.docker.com/config/daemon/ipv6/`
* port and domain name are set correctly in `default.conf`
* your domain is attached to Cloudflare  `https://www.notion.so/Podpi-cie-domeny-przez-CloudFlare-2a04b845203a4d9b82fa1816c6962d8e` or you can use a subdomain from `bieda.it`

### Author

Jarosław Kozioł
[@linkedin](https://www.linkedin.com/in/jaroslaw-koziol/)

### Version History

* 0.1
    * Initial release

### Acknowledgments

Used static website from:
* [ Nanaako ] (https://github.com/Nanaako)
