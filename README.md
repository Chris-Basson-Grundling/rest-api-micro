# rest-api-micro


docker-compose up
docker-compose down --remove-orphans --volumes
docker-compose up --build

After successful testing of the application, you can shut it down using:
docker-compose down
Or to also remove the volumes too:
docker-compose down --remove-orphans --volumes
If you want to remove all dangling images, run:
docker system prune
To remove all unused images, not just dangling ones, run:
docker system prune -a
To remove all unused images not just dangling ones and volumes, run:
docker system prune -a --volumes