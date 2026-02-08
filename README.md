The docker compose file for my Jellyfin-GlutenVPN

the only thing you need to change is the VPN serivice. for example:

    environment:
      - VPN_SERVICE_PROVIDER=mullvad
      - VPN_TYPE=wireguard
      - WIREGUARD_PRIVATE_KEY=***********
      - WIREGUARD_ADDRESSES=*************
      - SERVER_CITIES=New York NY


this is basically the compose file from this repo https://github.com/Morzomb/All-jellyfin-media-server
I'm not sure if I made any modifications so I'm backing it up here.
