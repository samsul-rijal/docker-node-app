## Install docker compose 

1. ```bash
    curl -SL https://github.com/docker/compose/releases/download/v2.6.1/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose
    ```
2. ```bash
    sudo chmod +x /usr/local/bin/docker-compose
    ```
3. ```bash
    sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose 
    ```
4. ```bash
    sudo docker-compose version
    ```

## Run App
```bash
sudo docker-compose -f docker-compose.yml up -d --build
```

link reference install : [https://docs.docker.com/compose/install](https://docs.docker.com/compose/install/compose-plugin/#install-using-the-repository)