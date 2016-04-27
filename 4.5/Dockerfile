FROM kibana:4.5

# make sure we run the commands as the kibana user
RUN gosu kibana kibana plugin --install elasticsearch/marvel \
 && gosu kibana kibana plugin --install elastic/sense
