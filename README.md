# es-java-client-sample
 Prerequisite : Java 8 and Later version 

### Start ElasticSearch
1) Download elasticsearch from [here](https://www.elastic.co/downloads/elasticsearch)   
2) Extract downloaded elasticsearch     
3) cd elasticsearch-X.X.X       
4) $ bin/elasticsearch     

### Insert data into elasticsearch
     $ curl -XPOST localhost:9200/test/tweet   -d '{"name":"Vinay", "job":"Program Architect" , "location":"USA", "age":32}'
     $ curl -XPOST localhost:9200/test/tweet   -d '{"name":"Tom", "job":"consultant" , "location":"US", "age":22}'
     $ curl -XPOST localhost:9200/test/tweet   -d '{"name":"Sander", "job":"Manager" , "location":"Germany", "age":25}'
 

### Run project 
    $ mvn package
    $ mvn exec:java -Dexec.mainClass="com.es.app.ESApp"

# ElasticSearch-Java-Client
