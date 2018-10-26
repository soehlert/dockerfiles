FROM python:3.7-alpine
LABEL name=black version=1.0 \
    maintainer="Sam Oehlert <sam.oehlert@gmail.com>"

RUN apk add openssh-client git && \
    addgroup -S black && adduser -D -S black black && \
    pip install black==18.9b0 && \
    mkdir /src

USER black

CMD ["black"]
