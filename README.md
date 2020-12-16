# books-docker
We “Dockerize” our Django project via Linux containers which are a type of virtualization.
Docker is lightweight and faster. Linux containers rely on the same Linux operating system. With Docker we
simply share two files–a `Dockerfile` and `docker-compose.yml` file–and we can have
confidence that our local development environment is exactly the same as the rest of the team. 
## 專案內容
1. 設定 Dockerfile 幫助建立 image
2. 設定 docker-compose.yml 幫助建立 web 和 db (PostgreSQL) 服務
3. 同步檔案系統: volumes mount in our `docker-compose.yml` file, which automatically syncs
the local and Docker filesystems. 


