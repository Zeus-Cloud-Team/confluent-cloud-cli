# Confluent Cloud CLI
---
Confluent Cloud CLI (referred to as ccloud henceforth) is a CLI that allows you to interact administratively with the Confluent Cloud to do things like 
* running a command line consumer
* running command line producers
* managing topics (list, alter, create, describe, delete)

**To install ccloud on a mac** do the following:
1. brew tap confluentinc/ccloud
2. brew install ccloud

[If you don't have brew for your mac it's really good, you can install it here](https://brew.sh/ ".sh stands for St. Helenas, where Napoleon was jailed").  Once installed run `ccloud init` and it will ask you for some information.  [See the ccloud-init.properties file for help](https://github.com/Zeus-Cloud-Team/confluent-cloud-cli/blob/master/ccloud-init.properties)

