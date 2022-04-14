**What is Elastic search ?**

Its a open-source software.
Full text search engine.
Its fast because of its Internally Distributed system.
Contains both - structured(RDMBS) and unstructured(JSON format).
All datas are in documents in JSON format.
Autocomplete / Instant search options also available.
Its used for logging in microservices(because centralized system).
Data migration is easy.
It contains nodes,clusters.

**Node** - single machine in a production environment running elasticsearch.  
The largest abstraction in elasticsearch is a **cluster.** A cluster contains one or more nodes.  
**Data nodes** — Stores data and performs operations related to data (aggregation/ search).  
**Master nodes** — Controls configuration and management across the cluster (adding / removing nodes).  
**Coordination only nodes** — These are nodes that have all other roles disabled. The only function this type of nodes perform is forwarding/routing requests to the relevant master/data nodes. These basically load balancers.  
**Ingest nodes** — Pre-process documents before inserting them into elasticsearch.  


**What is ELK ?**

Its an Architeture.
ELK - ElasticSearch & Logstash & Kibana.

Logstash - contains logs of all configured microservices running.
Elastic search - search/filter datas from DB.
Kibana - used to view elastic search results in a neat UI .

![Elastic search - process](https://user-images.githubusercontent.com/56901958/163419516-4a50ddc7-d1fd-4bab-a5f0-a1367d308c89.JPG)



**Download :**

ElasticSearch : https://www.elastic.co/downloads/elasticsearch

Logstash : https://www.elastic.co/downloads/logstash

Kibana : https://www.elastic.co/downloads/kibana