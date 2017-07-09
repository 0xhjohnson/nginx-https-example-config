# Nginx HTTPS Example Config

## Simple config to get LetsEncrypt running on Nginx server


Assumes you are follwing the [Digital Ocean guide](https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-16-04) and making a config snippet.

Areas that require changing to your specic domain:

`server_name www.example.com;`

`include snippets/ssl-www.example.com.conf;`

This is a basic config that can easily be expanded to suit your specific needs.
