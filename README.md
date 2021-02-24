# Example Cesium JS App

This repo contains a barebones example of Cesium JS app running in docker
image. Specifically it utilized Celestrak TLE data from the various Global
Navigation Satellite Systems (GNSS) and plots it around a globe of the Earth.

### Installation

The image can be created and ran as follows:

```
git clone https://github.com/rbisewski/cesiumjs-example-app.git
cd cesiumjs-example-app
docker-compose up -d
```

Afterwards you can access the web page at the below location:

```
http://localhost:8080
```
