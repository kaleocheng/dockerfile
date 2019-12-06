FROM alpine
RUN sed -i -e 's/v[[:digit:]]\..*\//edge\//g' /etc/apk/repositories
RUN apk add --no-cache nodejs npm py-pygments sassc hugo

