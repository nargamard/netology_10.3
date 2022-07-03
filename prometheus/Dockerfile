FROM alt:latest

ADD https://github.com/prometheus/prometheus/releases/download/v2.36.2/prometheus-2.36.2.linux-amd64.tar.gz .
RUN tar xvzf prometheus-2.36.2.linux-amd64.tar.gz --directory /bin/
WORKDIR /bin/prometheus-2.36.2.linux-amd64
ENV PATH=${PATH}:/bin/prometheus-2.36.2.linux-amd64
COPY prometheus.yml .

CMD [ "prometheus" ]