FROM alpine:latest

RUN apk update
RUN apk add git

ENV REPO_URL https://github.com/badyornyi/itea_devops_basecourse.git
WORKDIR /data
VOLUME /data

CMD sh -c "git clone $REPO_URL"
