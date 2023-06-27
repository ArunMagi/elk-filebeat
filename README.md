# elk-filebeat

create the pv  for elastic search with 30 gib

clone the repository

install all with helm chart 

if kibana dashbord giving warning 

vi /config/elasticsearch.yml

add this
 
xpack.security.enabled: false

