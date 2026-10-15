#Versione di linux
FROM alpine:latest

#Installazione curl
RUN apk add --no-cache curl

#While true di curl verso nginx per generare log
CMD ["sh", "-c", "while true; do curl -s 'http://my-nginx-svc:80'; sleep 15; curl -s 'http://my-nginx-svc:80/prova'; sleep 30; done"]
