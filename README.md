# Docker Flask and Heroku

This is the working foundation for application development using docker swarm, flask and heroku


## Getting Started

The first step is prepare the local environment use Docker Machine and Docker Swarm, follow [this link](https://docs.docker.com/get-started/part4/) to create Docker Machine.

Serving you is in an env docker-machine to run all script.


Build docker image in folder __/app__ and __/nginx__.

```
docker build --tags=<your-image-name> /app
docker build --tags=<your-image-name> /nginx
```

Create docker stack.

```
docker stack deploy -c docker-compose <your-stack-name>
```


## Deploy to Heroku

First create an account on Heroku.
And create apps from the CLI in [this link](https://devcenter.heroku.com/articles/creating-apps)

And deploying with Docker, follow [this link](https://devcenter.heroku.com/categories/deploying-with-docker)
