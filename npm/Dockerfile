FROM alpine:3.6

RUN apk add --no-cache nodejs-current nodejs-npm && npm install -g npm

ENV NPM_CONFIG_CACHE /tmp/npm
ENV XDG_CONFIG_HOME /tmp

WORKDIR /workdir/

ENTRYPOINT [ "npm" ]
