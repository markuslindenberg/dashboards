# Grafana Dashboards

Grafana dashboards I created.

## SNMP

Interface status and traffic graphs for [Prometheus SNMP Exporter](https://github.com/prometheus/snmp_exporter).

![SNMP dashboard screenshot](SNMP.png)

## ICMP

Blackbox ICMP check dashboard using [Prometheus Blackbox Exporter](https://github.com/prometheus/blackbox_exporter).

![ICMP dashboard screenshot](ICMP.png)

## Ping

Dashboard for [ping exporter](https://github.com/czerwonk/ping_exporter).

![Ping dashboard screenshot](Ping.png)

## APC UPS

Status dashboard for APC UPS using [Prometheus SNMP Exporter](https://github.com/prometheus/snmp_exporter).

![APC UPS dashboard screenshot](APCUPS.png)

## OpenWRT Wifi

Status dashboard for OpenWRT using the OpenWRT included exporter:

```
opkg update && opkg install prometheus-node-exporter-lua prometheus-node-exporter-lua-wifi prometheus-node-exporter-lua-wifi_stations
```

![OpenWRT Wifi dashboard screenshot](OpenWRT-Wifi.jpeg)

