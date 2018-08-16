Environment Setup:

1. Concourse - (Referrence: https://concoursetutorial.com/)

1.1 Install Docker.
1.2 Install Docker Compose if not included in your Docker installation.
1.3 Deploy Concourse using Docker Compose:

wget https://raw.githubusercontent.com/starkandwayne/concourse-tutorial/master/docker-compose.yml
docker-compose up -d

1.4 Open http://127.0.0.1:8080/ in your browser:
1.5 Click on your operating system to download the fly CLI.

Once downloaded, copy the fly binary into your path ($PATH), such as /usr/local/bin or ~/bin. Don't forget to also make it executable. For example,

sudo mkdir -p /usr/local/bin
sudo mv ~/Downloads/fly /usr/local/bin
sudo chmod 0755 /usr/local/bin/fly
