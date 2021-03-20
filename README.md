#Learning Docker

#commands

Run docker to a locally mapped drive
docker run -it -p 3000:3000 -v /app/node_modules -v "/c/Users/derek/Desktop/Learning Docker/Learning-Docker-Reference/ReactApp/frontend:/app" -e CHOKIDAR_USEPOLLING=true !!!!!node_id!!!!!

-v to map it outside

-v + : to map it inside

-e CHOKIDAR_USEPOLLING=true - windows stuff