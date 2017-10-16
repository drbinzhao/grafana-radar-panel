# Description

This grafana panel displays radar graphs using the Chart.JS library. (http://www.chartjs.org/)

The plugin was tested with Elastic Search 5.5 as data source.

## Installation

Copy the dist folder in your grafana plugin directory and rename it to radarpanel.

# Screenshots

## Showcase

![Radar](https://raw.githubusercontent.com/snuids/grafana-radar-panel/master/src/img/screenshot-radar-showcase.jpg)
![Radar](https://raw.githubusercontent.com/snuids/grafana-radar-panel/master/src/img/screenshot-radar-showcase2.jpg)

## Metrics Configuration

The panel datasource must include a single query having the following characteristics:
* A single group (No date histogram)
* Two groups (No date histogram)
* Three groups and the last group is a date histogram (As shown in the following screenshot)


![Radar](https://raw.githubusercontent.com/snuids/grafana-radar-panel/master/src/img/screenshot-radar-metrics.jpg)
![Radar](https://raw.githubusercontent.com/snuids/grafana-radar-panel/master/src/img/screenshot-radar-metrics2.jpg)

## Panel Options

![Radar](https://raw.githubusercontent.com/snuids/grafana-radar-panel/master/src/img/screenshot-rad-options.jpg)
