# README

## Introduction

This is a quick Vagrant environment to try ElasticStack. It should bring you a quickstart 
ElasticStack environment in 1 minute!

**By default we installed:**

- Elasticsearch: 7.6.2
- Kibana: 7.6.2
- Filebeat: 7.6.2

## Quickstart

```shell
# (Spawn up this vagrant box environment)
vagrant up

# (Login to the VM)
vagrant ssh

# (Trigger the filebeat setup, it's optional!)
sudo filebeat setup
```

## Start

Open [http://localhost:5601/](http://localhost:5601/) and enjoy!
