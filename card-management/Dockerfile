# This is a sample Dockerfile with a couple of problems.
# Paste your Dockerfile here.

FROM java:8-jdk-alpine

WORKDIR /home/app/

ADD target/cardmanagement-0.0.1-SNAPSHOT.jar /home/app/app.jar

ENTRYPOINT [ "sh", "-c", "java -Xmx2000m -jar /home/app/app.jar" ]