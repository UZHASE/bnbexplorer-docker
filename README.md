# BnB Explorer Docker
Local Docker development environment for BnB Explorer
## Prerequisites
Docker and Docker compose must be installed on you system.
[How to](https://docs.docker.com/get-docker).
## Setup
1. Create a new directory on your system (e.g. `bnbexplorer/`) and cd in it:
2. Run ``git clone git@github.com:UZHASE/bnbexplorer-docker.git``
2. Run ``git clone git@github.com:UZHASE/bnbexplorer-frontend.git``
3. Run ``git clone git@github.com:UZHASE/bnbexplorer-backend.git``

This should give you the strucutre:
```
   |-bnbexplorer/
        |-bnbexplorer-docker/
        |-bnbexplorer-frontend/
        |-bnbexplorer-backend/
```
4. Run `cd bnbexplorer-docker`
5. Run `docker-compose build`
6. Run `docker-compose up`
7. Open a browser on [localhost:3000](localhost:3000)
