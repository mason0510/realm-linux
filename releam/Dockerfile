FROM alpine:3.9

ARG VERSION="v2.3.4"

WORKDIR /realm

RUN wget https://github.com/zhboner/realm/releases/download/${VERSION}/realm-x86_64-unknown-linux-musl.tar.gz \
  && tar -zxvf realm-x86_64-unknown-linux-musl.tar.gz \
  && cp realm /usr/bin/realm \
  && chmod +x /usr/bin/realm

ENTRYPOINT ["/usr/bin/realm"]

