# arm-docker-sftp
Runs sftp from a docker container for ARM devices like RPI or Odroid.

## First start
Create a file users.conf in the $HOST_PATH
The file should be under this format: "login":"password"


## Docker Compose
Please check the `.env` file and change it at your conveniance $PORT and $HOST_PATH  
Then: `docker-compose run sftp or docker-compose up or docker-compose up -d (to detach it)`


