# dockerized-todo-app-flask-reactjs

image building cmnds
docker frontend image
base image is node:22-alpine3.21 
created working directory and copied package.json files then install npm and all dependencies from the package.json files
exposed port : 5173
CMD arguemnets npm run dev and 0.0.0.0 to run this on all host  


docker compose

running both images container in a network and running both container at once 
docker push to the docker hub repository
docker login, tag, push to the hub 

to run this dockerized application
docker compose up --build 

access frontend http://localhost:5173/dashboard

access backend http://localhost:5000/docs 