## MARIADB Container for Development
## Downloading from Repo
### Cloning from Repo
- Clone using ssh 
    ```
    git clone git@192.168.197.15:docker-hub/mariadb.git
    ```
### Cloning to diffrent directory

- Create and Change to created diretory
    ```
    mkdir <custom directory>
    cd <custom directory>
    ```

- Initialize git repo
    ```
    git init
    ```

- Create main branch
    ```
    git switch --create main
    ```

- Add remote repo
    ```
    git remote add origin git@192.168.197.15:docker-hub/mariadb.git
    ```

- Git pull from remote 
    ```
    git pull origin main
    ```
## Running the container
- To start the MariaDB container in detached mode.
    ```
   docker compose up -d
   ```

- To stop the container.
    ```
   docker compose down
   ```