# OSM-Crosswalk-Detection

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md)

## Docker image for OSM-Crosswalk-Detection

This image is used for the OSM-Crosswalk-Detection project.
You can directly start the different worker roles described in the next paragraph.

## How to use

```bash
#Manager
docker run murthy10/osm-crosswalk-detection python /root/OSM-Crosswalk-Detection/src/role/main.py --role manager left bottom right top

# Jobworker
docker run murthy10/osm-crosswalk-detection python /root/OSM-Crosswalk-Detection/src/role/main.py --role jobworker

# Resultworkerdocker
run murthy10/osm-crosswalk-detection python /root/OSM-Crosswalk-Detection/src/role/main.py --role resultworker
```