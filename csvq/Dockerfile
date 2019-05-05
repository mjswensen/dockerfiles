FROM alpine:latest

RUN wget https://github.com/mithrandie/csvq/releases/download/v1.10.6/csvq-v1.10.6-linux-386.tar.gz \
  && tar -xf csvq-v1.10.6-linux-386.tar.gz \
  && rm csvq-v1.10.6-linux-386.tar.gz \
  && ln -s /csvq-v1.10.6-linux-386/csvq /usr/local/bin/csvq
