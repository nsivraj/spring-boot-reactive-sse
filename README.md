# Spring Boot Reactive Webflux Server-Sent Events

This is a sample application that shows how to use Server-Sent Events using:
 - Spring Boot 2
 - Spring Webflux


<br/>
Please see the following pages for more details

  - Spring Web Reactive <br/><a>https://docs.spring.io/spring-framework/docs/5.1.2.RELEASE/spring-framework-reference/web-reactive.html</a>

## Running

Run this using using the gradle wrapper included

```
./gradlew bootRun
```

This will start the application on port 8080.


## cURL Commands

You can try the following API once the server is running.

GET __/stock/transaction__

``` curl -v http://localhost:8080/stock/transaction```

## For SSL
cd src/main/resources
keytool -genkey -keyalg RSA -alias streamingserver -keystore keystore.jks -deststoretype pkcs12 -storepass password -validity 2000 -keysize 2048


https://github.com/mohitsinha/spring-boot-reactive-sse.git

https://medium.com/@nithinmallya4/processing-streaming-data-with-spring-webflux-ed0fc68a14de

https://medium.com/vividcode/spring-5-webflux-with-server-sent-events-707be6156909

https://github.com/eugenp/tutorials


