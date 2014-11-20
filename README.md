solr
====

Docker container for EOL's Solr on debian


    sudo docker run --rm --name solr  -p 8983:8983 -v /home/dimus/data/solr:/opt/cores/solr solr:4.10.2
