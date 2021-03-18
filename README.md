# Nordic Energy ETH Bridge Frontend

#### Ethereum<>Nordic Energy two way bridge (development version)



## Install instructions

### Requirements 

* nodejs 

### Commands

* Fetch repo 

```
git clone git@github.com:nordicenergy/ethnet-bridge-frontend.git
```

* Install dependencies

```
npm install
```

* Develop

```
npm run dev
```

* Build

```
npm run build
```

* Start

```
cd build 
serve
```

# Docker

## build
```
./build.sh
```

The build artificats will be in artifacts/build folder.

## Start
```
./start.sh
```
The frontend will be started in http://localhost:8080

## push to docker hub
You need to have permission to push to the nodicenergy repo.

```bash
sudo docker login
sudo docker tag ethhmy-fe-web nordicenergy/ethnet-fe-web:latest
sudo docker push nordicenergy/ethnet-fe-web
```

You may also push to difference release version other than just `latest`.
# nordicenergy-bridge-frontend
