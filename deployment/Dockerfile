FROM abutaha/aws-es-proxy:latest
LABEL MAINTAINER Cristian Casis <crcasis@viesure.io>

CMD ["sh", "-c", "aws-es-proxy -listen es-proxy:9200 -endpoint ${ENDPOINT}"]