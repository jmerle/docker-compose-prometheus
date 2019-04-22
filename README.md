# Traefik Prometheus

A Docker Compose configuration to run [Prometheus](https://prometheus.io/), [Alertmanager](https://github.com/prometheus/alertmanager) and [Pushgateway](https://github.com/prometheus/pushgateway) behind a [Traefik](https://traefik.io/) reverse proxy.

## Usage

1. Clone this repository.
2. Copy `.env.example` to `.env` and modify the variables.
3. Copy `prometheus-example` to `prometheus` and adapt it's configuration to your needs.
4. Copy `alertmanager-example` to `alertmanager` and adapt it's configuration to your needs.
5. Run `docker-compose up -d`.
