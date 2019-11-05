# portainer-cn

    docker volume create portainer_data
    docker run -d -p 9000:9000 --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data -v /Portainer-CN:/public --name portainer portainer/portainer:1.20.2

