# flask-cripto 

### This is the final project for the Keepcoding bootcamp

## How to deploy this project

This project has been dockerized so to be able to be run in your environment you need to have Docker installed, if it's not already installed, please, follow the steps described on the [Docker documentation](https://docs.docker.com/engine/install/)

1. Clone the repository to your local machine

```
git clone https://github.com/enelombopaez/flask-cripto.git
```

2. Build the docker image, this command has to be run on the same folder as the Dockerfile

```
docker build --tag python-docker .
```

3. Run the docker image

```
docker run -d -p 5001:5000 python-docker
```

4. Open the browser and go to `localhost:5001`


## Do you want to contribute?

This is a public and open source project so feel free to contribute or use this code for your own purpose. In case you prefer to contribute directly to this repository, please, follow the steps described below


1. Clone the repository to your local machine

```
git clone https://github.com/enelombopaez/flask-cripto.git
```

