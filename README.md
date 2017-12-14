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

**To install ccloud on a Windows PC** do the following:

Download the zip file from the slack channel unzip it and run bin/ccloud init.  You will be prompted for the bootstrap broker list found [here](https://github.com/Zeus-Cloud-Team/confluent-cloud-cli/blob/master/ccloud-init.properties) API Key and API Secret found in the slack channel.  

**To install ccloud on a linux PC** do the following:

Download the tarball file from [here](https://s3-us-west-2.amazonaws.com/confluent.cloud/cli/ccloud-latest.tar.gz) extract the files and run bin/ccloud init.  You will be prompted for the bootstrap broker list found [here](https://github.com/Zeus-Cloud-Team/confluent-cloud-cli/blob/master/ccloud-init.properties) API Key and API Secret found in the slack channel.

