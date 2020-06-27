## InfluxDB RaspberryPi 4 DockerImage

To create the build and tag it run 
`docker build -t influxdb-rpi .`

To start the container with a persitent colume run
`docker run --name influxdb -d -p 8086:8086 influxdb-rpi`
