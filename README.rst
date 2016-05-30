
Requirement
------------
To use these filter you need to have ELKstack in your system.
Please download elasticsearch ,logstash and kibana from given below link.
https://www.elastic.co/downloads 

Setup
------------
1)Run Elasticsearch either by services command or manually.
  cd elasticsearch-version_number
  
  bin/elasticsearch
  
2)Run Logstash and filterforlog.conf consist of cleaning of log file with almost each type data in log file
  cd logstash-version_number
  
  bin/logstash -f filterforlog.conf
  
Filters Overview
-----------------
1)apache-elasticsearch.conf: The file consist of code to clean apache log file data.
 
2)jason.conf:The file consist of code to see the aplication of  codec json log data.

3)nginx.conf: TThe file consist of code to clean nginx log file data.

4)filterforlog.conf:The file consist of code to clean complex log which contain nested dictionary/hash ,dynamic keys,nested arrays,simple arrays and hash,string and constant.

5)filterwithmongo_elastic.conf:The file consist of functionality similar to filterforlog.conf and output will be stored in elasticsearch as well in mongo for further analysis.
