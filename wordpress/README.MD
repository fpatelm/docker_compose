mkdir  ~/wordpress-compose && cd ~/wordpress-compose
docker-compose up -d
# Starts all stopped containers in the work directory
docker-compose start
# Stops all currently running containers in the work directory
docker-compose stop
# Validates and shows the configuration
docker-compose config
# Lists all running containers in the work directory
docker-compose ps
# Stops and removes all containers in the work directory
docker-compose down