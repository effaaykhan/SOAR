# SOAR
This repo contains the installation and configuration of SOAR (Shuffle, MISP, TheHIve, and Cortex.

## Shuffle
i) Add [custom-shuffle.py](https://github.com/effaaykhan/SOAR/blob/main/Shuffle/custom-shuffle.py) and [custom-shuffle](https://github.com/effaaykhan/SOAR/blob/main/Shuffle/custom-shuffle) in ```/var/ossec/integrations``` on the server where Wazuh is running.

ii) Create directories the following directories
```
mkdir SOAR
mkdir shuffle
```
iii) Create the following file to install shuffle and add the [docker-compose.yml](https://github.com/effaaykhan/SOAR/blob/main/Shuffle/docker-compose.yml) contents to it.
```
nano docker-compose.yml
```

## MISP, CORTEX & THEHIVE
i. Create the following docker-file to install misp, cortex and thehive and add the [docker-compose.yml](https://github.com/effaaykhan/SOAR/blob/main/MISP-CORTEX-THEHIVE/docker-compose.yml)
```
nano docker-compose.yml
```
