# Introduction to Google Cloud Operations Suite
This file contains text you can copy and paste for the examples in Cloud Academy's _Introduction to Google Cloud Operations Suite_ course.  

### Logging
```
select * from example_dataset.syslog_<date> WHERE jsonPayload.message LIKE '%shutdown%'
```

### Error Reporting
[Google Cloud SDK](https://cloud.google.com/sdk)  
[Java SE 11 Development Kit](https://www.oracle.com/java/technologies/downloads/#java11)  
[Git](https://git-scm.com/downloads)  
[Maven 3.5 or greater](https://maven.apache.org/download.cgi)  

```
git clone https://github.com/GoogleCloudPlatform/java-docs-samples
cd java-docs-samples/appengine-java11/springboot-helloworld
mvn spring-boot:run
gcloud app deploy
```
```
int bad = 1/0;
```
