# Use the latest Tomcat image
FROM tomcat:latest

# Copy the default web applications to the webapps directory
RUN cp -R /usr/local/tomcat/webapps.dist/* /usr/local/tomcat/webapps

# Copy the WAR file from the specified directory to the Tomcat webapps directory
COPY hello-world/webapp/target/*.war /usr/local/tomcat/webapps/

# Expose the port that Tomcat is running on
EXPOSE 8080

# Start Tomcat (this is done automatically by the base image)


