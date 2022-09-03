# PufferPanel-docker-compose

A docker compose file to deploy PufferPanel with a nginx reverse proxy 

1. Clone this repository `` git clone https://github.com/NereaCassian/PufferPanel-docker-compose.git ``

2. Configure in the nginx/nginx.conf file your domain an ssl cert and key
3. Put your ``.crt`` and your ``.key`` on the ``/ssl`` directory
4. Put your especifig configuration in the ``/config/config.json`` file or leave it empty
5. Run ``docker compose up -d``
6. Run ``docker exec -it pufferpanel /pufferpanel/pufferpanel user add``
7. You have it running

The original Pufferpanel repo 
https://github.com/pufferpanel/pufferpanel
