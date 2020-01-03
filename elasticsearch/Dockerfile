# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch

RUN chmod -R 0777 /usr/share/elasticsearch

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu

RUN sudo sysctl -w vm.max_map_count=262144
RUN sysctl -p
