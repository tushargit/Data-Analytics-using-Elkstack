# Data-Analytics-using-Elkstack

Requiremnt
------------
To use these filter you need to have ELKstack in your system.
Please download elasticsearch ,logstash and kibana from given below link.
https://www.elastic.co/downloads 

Setup
------------
1)Run Elasticsearch either by services command or manually.
  cd elasticsearch-version_number
  
  bin/elasticsearch
  
2)Run Logstash and filterforlog.conf consist of cleaning of log file with almost every type data in log file
  cd logstash-version_number
  
  bin/logstash -f filterforlog.conf
 
