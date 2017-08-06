# MythTV Exporter for Prometheus 

This is a simple server that scrapes MythTV stats and exports them via HTTP for [Prometheus](http://prometheus.io) consumption.


## Getting Started

To run it:

```bash
./mythtv_exporter [flags]
```

Help on flags:

```bash
./mythtv_exporter --help
```

## Installation

```
pip install prometheus_client
```

## License

Apache License 2.0, see [LICENSE](https://github.com/thknepper/mythtv_exporter/blob/master/LICENSE).
