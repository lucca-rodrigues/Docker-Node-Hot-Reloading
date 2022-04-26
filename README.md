# Docker-Node-Hot-Reloading
- Example to configure environment develop with Docker/Node and Express

# Run and Share Volume with Container
- From executing the container configs you precisely run:
```
docker run --rm -it -v $(pwd)/:/usr/src/app -p 3000:3000 node:15 bash
```
- If runner, your local folder is created and shared by Docker container

- Run your app container in bash container:
```
npm run start
```
