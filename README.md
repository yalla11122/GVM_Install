# GVM_Install

sudo pacman -Syu docker docker-compose curl ca-certificates gnupg
  
  sudo systemctl enable --now docker
 
     sudo usermod -aG docker $USER && newgrp docker
   
    export DOWNLOAD_DIR=$HOME/greenbone-community-container

    mkdir -p "$DOWNLOAD_DIR"
  


     cd "$DOWNLOAD_DIR"

curl -f -O -L https://greenbone.github.io/docs/latest/_static/docker-compose.yml
curl -f -O https://greenbone.github.io/docs/latest/_static/setup-and-start-greenbone-community-edition.sh
    
    chmod +x setup-and-start-greenbone-community-edition.sh

 ./setup-and-start-greenbone-community-edition.sh

set USER/PASS

        https://127.0.0.1:9392

     
     ....Feed is currently syncing.

    Please wait while the feed is syncing. Scans are not available during this time. For more information, visit the Documentation.
    Filter
 
