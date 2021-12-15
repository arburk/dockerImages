FROM docker:20.10-git

RUN  apk update \
  && apk upgrade \
  && apk add ca-certificates \
  && update-ca-certificates

RUN apk add --update --no-cache unzip curl openjdk11

ENV MAVEN_HOME /usr/lib/mvn
ARG MAVEN_VERSION=3.8.4
ARG MAVEN_BASE_URL=https://downloads.apache.org/maven/maven-3/${MAVEN_VERSION}/binaries
RUN mkdir $MAVEN_HOME && \
    curl -fsSL -o /tmp/apache-maven.tar.gz ${MAVEN_BASE_URL}/apache-maven-${MAVEN_VERSION}-bin.tar.gz && \
    tar -zxvf /tmp/apache-maven.tar.gz -C $MAVEN_HOME --strip-components=1 && \
    rm -f /tmp/apache-maven.tar.gz

RUN mkdir /tmp/src && cd /tmp/src

CMD ["sh", "-c", "cd /tmp/src && ./execute.sh"]
