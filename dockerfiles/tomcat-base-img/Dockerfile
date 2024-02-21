FROM tomcat:10.1.16-jdk21-temurin-jammy

# Expose Tomcat's default port (optional)
EXPOSE 8080

# Define environment variable to enable virtual threads 
ENV JAVA_OPTS="-XX:+UnlockExperimentalVMOptions -XX:+UseZGC -XX:+UseNUMA -XX:+UseParallelGC -XX:+UseVirtualThreads"
COPY server.xml /usr/local/tomcat/conf
