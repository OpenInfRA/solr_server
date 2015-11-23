# solr_server
This repository contains the Solr Server for OpenInfRA.

# Installation and configuration
[Solr](http://lucene.apache.org/solr/) can be used as stand alone installation. It contains its own web server. You can place Solr somewhere in your file system. To start Solr use the following command from the [bin directory](solr-5.3.1/bin/
) and replace _[path/to/core]_ with the path of the core (e.g. [OpenInfRA Solr core](https://github.com/OpenInfRA/solr_core)) you want to use: `solr -s [path/to/core]`

To stop the server simply execute the following command and replace _[port]_ with the port Solr was started at: `solr -p [port]`
