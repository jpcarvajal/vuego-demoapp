docker-compose up gets the error ports must be a list even when trying with code from other students that worked and found no solution, the containers can be created individually though.

docker run --name frontend -p 5000:80 -d frontend
docker run --name backend -p 4001:4001 -d backend