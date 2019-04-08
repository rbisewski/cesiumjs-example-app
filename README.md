# Example Cesium JS App

This repo contains a barebones example of Cesium JS app running in docker
image. Specifically it utilized Celestrak TLE data from the 2019 Indian ASAT
test and plots it on a globe of the Earth.

### Installation

The image can be created and ran as follows:

```
git clone https://github.com/rbisewski/cesiumjs-example-app.git
cd cesiumjs-example-app
docker build -t cesiumjs-example-app:19.04 .
docker run --name cesium-test -d -p 8080:80 cesiumjs-example-app:19.04
```

Afterwards you can access the web page at the below location:

```
http://localhost:8080
```
