# Prisma Cloud metrics and monitoring

[![license](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE) [![support](https://img.shields.io/badge/Support%20Level-Community-yellowgreen)](./SUPPORT.md)

## !!! BY DEFAULT PROMETHEUS IS NOT AUTHENTICATED !!!
Be sure to secure Prometheus, unauthenticated by default

### Required config
Edit [./prometheus/prometheus.yml](./prometheus/prometheus.yml) with your `Path to Console` and access/secret key

### Data Sources
Append new data sources in [/grafana/provisioning/datasources/all_sources.yml](./grafana/provisioning/datasources/all_sources.yml)

### Dashboards
Add new `.json` files of dashboards in [./grafana/dashboards](./grafana/dashboards/)

## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details