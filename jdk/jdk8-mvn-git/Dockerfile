FROM iron/java:1.8-dev

RUN apk add --no-cache git

RUN MAVEN_VERSION=3.3.9 \
 && cd /usr/share \
 && wget -q http://apache.dattatec.com/maven/maven-3/$MAVEN_VERSION/binaries/apache-maven-$MAVEN_VERSION-bin.tar.gz -O - | tar xzf - \
 && mv /usr/share/apache-maven-$MAVEN_VERSION /usr/share/maven \
 && ln -s /usr/share/maven/bin/mvn /usr/bin/mvn