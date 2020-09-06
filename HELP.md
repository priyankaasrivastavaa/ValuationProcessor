# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.3.3.RELEASE/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.3.3.RELEASE/gradle-plugin/reference/html/#build-image)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/2.3.3.RELEASE/reference/htmlsingle/#using-boot-devtools)
* [Spring for Apache Kafka](https://docs.spring.io/spring-boot/docs/2.3.3.RELEASE/reference/htmlsingle/#boot-features-kafka)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)


docker build -t valuationprocessor

 docker run -p 9060:9060 -d valuationprocessor .


kafka-topics --create --topic valuation --bootstrap-server localhost:9092

kafka-topics --describe --topic valuation --bootstrap-server localhost:9092

kafka-console-producer --topic valuation --bootstrap-server localhost:9092

kafka-console-consumer --topic valuation --from-beginning --bootstrap-server localhost:9092



docker stop $(ps -a -q).