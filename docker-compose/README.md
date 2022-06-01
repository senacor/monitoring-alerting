# Minimal setup with docker-compose

For a minimal setup all needed components such as
- Grafana
- Prometheus Server
- Prometheus Node Exporter
- Prometheus Alertmanager
can be simply spun up as Docker containers and combined in a docker-compose file.

## Usage

To run the setup, simply execute the following command in the current directory:
> docker-compose up

Further:

- The Grafana UI can be reached under localhost:3000 (login credentials: username 'admin', password 'foobar'). The configuration for Grafana is defined in [config.monitoring](./grafana/config.monitoring).

- Prometheus also exposes a user interface which may be reached under localhost:9090. 
