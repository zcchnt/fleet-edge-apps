#Versione di linux
FROM alpine:latest

#Installazione curl
RUN apk add --no-cache curl

#While true di curl verso nginx per generare log
CMD ["sh", "-c", "while true; do curl -s http://192.168.1.200:30082; sleep 15; curl -s http://192.168.1.200:30082/prova; sleep 30; done"]