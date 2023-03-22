# ILTPWC - Episode "Lets encrypt our homelab with wildcard SSL certificates"

This repository contains the sourcecode shown in the ILTPWC video [Lets encrypt our homelab with wildcard SSL certificates](ADD YOUTUBE LINK LATER)

## Prerequisite

Your host need to have docker and docker-compose installed and you need to replace each <ADD_YOUR_XXX> variable with your credentials before starting the containers


## Get Started

1. Checkout the sourcecode
2. modify acme.json file permissions `sudo chmod 600 ./data-traefik/acme.json`
3. sudo docker-compose up -d

## Included Services to demonstrate use case

- Traefik | The reverse proxy that handles SSL/TLS termination
- httpd | Web server with a static hello ILTPWC page

# Call to action

If you like what I do please consider to (star & watch here on Github) or (like & subscribe to ILTPWC on YouTube) - Thanks a lot!
