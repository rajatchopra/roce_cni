FROM ubuntu:18.04

ADD show_gids.sh /
RUN apt -y update && \
        apt-get install -y librdmacm1 libibverbs1 ibverbs-providers iproute2 && \
        apt-get install -y perftest && \
        apt-get install -y vim iputils-ping


CMD ["/bin/bash"]
