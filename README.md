# Sylvy-Game-setup

Sylvy-Game-setup

## isntall docker-compose

sudo curl -L "https://github.com/docker/compose/releases/download/v2.2.3/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version

## install docker

sudo amazon-linux-extras install docker
sudo systemctl start docker
sudo systemctl enable docker
sudo usermod -a -G docker ec2-user

# RUN

docker-compose up -d

# 재시작

docker-compose down
docker-compose up -d --build
