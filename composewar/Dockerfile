FROM java:8
EXPOSE 8080

#src - dest
ADD /user-registration-application-0.0.1-SNAPSHOT.war userregistration.war 
ENTRYPOINT ["java","-jar","userregistration.war"]