# BnB Explorer Docker
## Open Project [Documentation](https://github.com/UZHASE/bnbexplorer-docker/wiki)

***
## Setup
Setup local Docker development environment for BnB Explorer
### Prerequisites
Docker and Docker compose must be installed on you system.
[How to](https://docs.docker.com/get-docker).
### Installation
1. Create a new directory on your system (e.g. `bnbexplorer/`) and cd in it:
2. Run ``git clone git@github.com:UZHASE/bnbexplorer-docker.git``
2. Run ``git clone git@github.com:UZHASE/bnbexplorer-frontend.git``
3. Run ``git clone git@github.com:UZHASE/bnbexplorer-backend.git``

This should give you the strucutre:
```
   .
   bnbexplorer/
        |-bnbexplorer-docker/
        |-bnbexplorer-frontend/
        └-bnbexplorer-backend/
```
4. Run `cd bnbexplorer-docker`
5. Run `docker-compose up`
6. Open a browser on [localhost:3000](localhost:3000)