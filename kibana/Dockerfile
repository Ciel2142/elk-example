ARG ELK_VERSION
FROM docker.elastic.co/kibana/kibana:${ELK_VERSION}

ARG ELK_VERSION
ARG SG_VERSION_KIBANA
RUN kibana-plugin install https://maven.search-guard.com/search-guard-kibana-plugin-release/com/floragunn/search-guard-kibana-plugin/${ELK_VERSION}-${SG_VERSION_KIBANA}/search-guard-kibana-plugin-${ELK_VERSION}-${SG_VERSION_KIBANA}.zip
