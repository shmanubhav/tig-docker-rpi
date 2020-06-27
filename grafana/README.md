## Grafana RaspberryPi 4 DockerImage

To create the build and tag it run 
`docker build -t grafana-rpi .`

To start the container with a persitent colume run
`docker run --name grafana -d -p 3000:3000 grafana-rpi`
