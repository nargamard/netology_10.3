FROM alt:latest

RUN apt-get update -y && apt-get install grafana -y

ENV PATH=${PATH}:/etc/grafana

CMD [ "grafana-server" ]

