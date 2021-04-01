FROM java:8
ADD target/offers-0.0.1-SNAPSHOT.jar /usr/local/offers-0.0.1-SNAPSHOT.jar
RUN chmod 755 /opt/startup/init_container.sh
CMD ["java","-jar/usr/local/offers-0.0.1-SNAPSHOT.jar"]