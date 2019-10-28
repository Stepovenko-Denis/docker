# Install
Downloads

`git clone git@github.com:Stepovenko-Denis/docker.git`

`cp .env.example .env`

Open file `.env` and set environment

Docker run

`cd docker && docker-compose up -d`

Configure your host

`echo '${NETWORK_PREFIX}.2 subdomain.domain.com' | sudo tee -a /etc/hosts`