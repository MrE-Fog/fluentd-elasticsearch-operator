# fluentd-elasticsearch

## Description

Fluentd is an open-source data collector for a unified logging layer. Fluentd allows you to unify data collection and
consumption for better use and understanding of data. This fluentd charm is specifically built to forward logs to
elasticsearch.

## Usage

```bash
juju deploy ./fluentd-elasticsearch_ubuntu-20.04-amd64.charm --resource fluentd-elasticsearch-image=gcr.io/google-containers/fluentd-elasticsearch:v2.4.0
```

## OCI Images

Default: gcr.io/google-containers/fluentd-elasticsearch:v2.4.0

## Contributing

Please see `CONTRIBUTING.md` for developer guidance.
