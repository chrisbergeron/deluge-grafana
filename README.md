# Deluge Grafana Dashboard

Deluge Dashboard is a very simple way to display [Deluge](https://deluge-torrent.org/) torrent metrics.  It uses the [Deluge Exporter](https://github.com/tobbez/deluge_exporter) to populate a [Prometheus](https://prometheus.io/) data source.  The panels in this dashboard can be copied into more comprehensive dashboards for a single pane of glass view of your network transfers or it can be used as a standalone glanceboard.

![Deluge Grafana](https://res.cloudinary.com/cyberge/image/upload/v1551153412/screenshots/amkeucb9bhfveijastbd.png)

To use, simply import the dashboard into Grafana using ID `9846`.

View the dashboard on [Grafana.org](https://grafana.com/dashboards/9846/)

### Manual Installation ###
You can copy/paste the raw .json data into Grafana via the `Dashboards` -> `Import` menu, or save the .json file and import the file.
