## InfluxDB RaspberryPi 4 DockerImage

To create the build and tag it run 
`docker build -t influxdb-rpi .`

To start the container with a persitent colume run
`docker run --name influxdb -d -p 8086:8086 influxdb-rpi`

Install telegraf on client nodes and place the config file
at `/etc/telegraf/telegraf.d/telegraf.conf` after replacing
the correct `hostname`
