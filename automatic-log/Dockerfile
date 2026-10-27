#Versione di linux
FROM alpine:latest

#Installazione curl
RUN apk add --no-cache curl

#While true di curl verso nginx per generare log
CMD ["sh", "-c", "while true; do curl -s 'http://my-nginx-svc.cluster.local:80'; sleep 5; done"]
