FROM alt:latest

ADD https://github.com/prometheus/node_exporter/releases/download/v1.3.1/node_exporter-1.3.1.linux-amd64.tar.gz .
RUN tar xvzf node_exporter-1.3.1.linux-amd64.tar.gz --directory /bin/
WORKDIR /bin/node_exporter-1.3.1.linux-amd64
ENV PATH=${PATH}:/bin/node_exporter-1.3.1.linux-amd64

CMD [ "node_exporter" ]

