# logstash-docker
Run logstash on docker


Command:

docker run --rm -it --net somenetwork -v "AddYouPath"\logstash.conf:/usr/share/logstash/pipeline/logstash.conf docker.elastic.co/logstash/logstash:7.6.0

somenetwork : docker network in which your ELK stack running.
logstash.conf : Your configuration file.
