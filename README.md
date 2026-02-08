The docker compose file for my Jellyfin-GlutenVPN

the onlything you need to change is the VPN serivice. for example.

    environment:
      - VPN_SERVICE_PROVIDER=mullvad
      - VPN_TYPE=wireguard
      - WIREGUARD_PRIVATE_KEY=***********
      - WIREGUARD_ADDRESSES=*************
      - SERVER_CITIES=New York NY
