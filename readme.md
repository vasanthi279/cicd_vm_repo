filebeat sg 
============
  22--myip

  8080---myip
  
  5044---to attach to the elasticserch sg 



elasticseach sg
================
22------myip

5601-----myip

9200------to attach to the filebeat sg




node exporter-sg
=================
22-----myip

9100---to attach to the prometheus sg




grafan-proemtheus-sg
=====================
22---myip

3000---myip

9090---myip

9090----to attach to the node exporter sg 