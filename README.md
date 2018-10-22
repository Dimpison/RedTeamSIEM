# Elastic for Red Teaming

## Overview

Repository of resources for configuring a Red Team SIEM using Elastic

Note: This repository is a companion to a talk given at BSides Pittsburgh 2018. 
- For details and slides, see http://securityriskadvisors.com/blog/bsides-pgh-2018-heavy-machinery-and-burly-lumberjacks-and-logging-oh-my/ 
- For the full recording, see https://www.youtube.com/watch?v=xH1TeVtG1M8

## Directory structure

```
.
├── ansible
│     └── Ansible playbooks for deploying an Elastic instance and configuring clients to forward the relevant logs 
├── elastalert
│     └── Elastalert example rules and configuration files
├── elastic
│     └── Example static configuration files
└── resources
      └── Resources for related services/technology such as Cobalt Strike
```

## Roadmap

- Investigate, configure and run cobaltstrike
- Review logs on all components of schema
- Set correct webhook url for elastalert
