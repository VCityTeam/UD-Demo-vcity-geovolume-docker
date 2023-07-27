## UD-Demo-Vcity-GeoVolume-Docker

Fully dockerized version of the [UD-Demo-Vcity-GeoVolume](https://github.com/VCityTeam/UD-Demo-vcity-geovolume.git) along with a [GeoVolumeServer](https://github.com/VCityTeam/GeoVolume-Server.git)

## Installation

This demo requires the Docker Engine. Installation instructions can be found [here](https://docs.docker.com/engine/install/).

Once Docker is installed, clone this repository and use the docker-compose file :
```
git clone https://github.com/VCityTeam/UD-Demo-vcity-geovolume-docker.git
cd UD-Demo-ccity-geovolume-docker
docker-compose up
```

By default (in the [.env](./.env)), the geoVolume Server will be hosted on [`localhost:3000`](localhost:3000)

By default (in the [.env](./.env)), the geoVolume Demo will be hosted on [`localhost:8000`](localhost:8000)
