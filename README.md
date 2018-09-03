<p><img src="http://1000logos.net/wp-content/uploads/2017/07/Logo-Docker-500x394.jpg" alt="docker logo" title="docker" align="right" height="60" /></p>

Ansible-Role-Docker-Collector
=========


Requirements
------------

 - Ansible >= 2.4
 - Docker and docker-py

Role Variables
--------------


| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `collector_container_name` | collectorfordocker  | Name of the Container |
| `collector_image` | outcoldsolutions/collectorfordocker:3.0.93.180531 | Docker Image (incl.tag) |
| `collector_splunk_url` | Ansible inventory group `splunk` | Splunk Server URL|
| `collector_splunk_token` | Variable `hec_token` | HEC Token for Splunk|


Author Information
------------------

## Author Information

You can find me on Twitter: [@itkombinat](https://twitter.com/itkombinat)
