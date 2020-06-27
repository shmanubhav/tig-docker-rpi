# rpi-docker
Telegraf, InfluxDB, Grafana stack running on a Raspberry Pi 4 using Docker
----
Install `docker-compose` from `https://docs.docker.com/compose/install/`

To start up the TIG (Telegraf, InfluxDB and Grafana) stack, run `docker-compose up -d`.

To bring fown the stack while keeping the persistent data volumes intact run `docker-compose down`
