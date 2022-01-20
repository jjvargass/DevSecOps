FROM alpine:latest

RUN apk add git jq --no-cache

# talisman v1.23.0
COPY talisman .
RUN chmod +x talisman && mv talisman /usr/local/bin
