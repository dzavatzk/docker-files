FROM alpine

LABEL maintainer "luky <luky@gmail.com>"

ADD python-textovka /python-textovka

RUN apk add python3 py3-pip

WORKDIR /python-textovka

CMD [ "/usr/bin/env", "python3", "game.py" ]
