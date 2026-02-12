FROM docker:29.2.0

RUN apk add --update bash

COPY run-elasticsearch.sh /run-elasticsearch.sh

ENTRYPOINT ["/run-elasticsearch.sh"]
