# Gateway Aggregator Pattern
https://github.com/mehedeehassan-paypay/web-flux-pattern

# HOW TO RUN
```
java -jar web-flux-pattern/external-service/external-service-v2.jar --server.port=7070

SET PROJECT JDK 21
RUN MAVEN APP
./mvnw spring-boot:run
```

## PROBLEM
- limitation of parallel call
- more extra feature
<img width="1180" alt="image" src="https://github.com/user-attachments/assets/218c3eeb-582b-4d43-8653-1de740ef57a5" />

## SOLUTION
<img width="1043" alt="image" src="https://github.com/user-attachments/assets/49cb5385-5075-41a6-b205-aba50a660443" />

## EXAMPLE

<img width="1336" alt="image" src="https://github.com/user-attachments/assets/6065f469-3954-4dcb-896d-cc041b29c713" />

<img width="1175" alt="image" src="https://github.com/user-attachments/assets/c053e0bc-4ee0-4a57-987f-0cd341b47410" />


# DEVELOPMENT


``
java -jar external-service.jar server.port=7000
``

<img width="1325" alt="image" src="https://github.com/user-attachments/assets/c9d1f7aa-e168-443c-85f0-1d432ee43683" />


## what we are doing

<img width="1226" alt="image" src="https://github.com/user-attachments/assets/f7ffe5e4-614d-42b0-b3a7-4afba1ea4b08" />




### CALL AGGREGATOR 
```
http://localhost:7070/swagger-ui/#/sec01-gateway-aggregator/getProductUsingGET
http://localhost:8080/sec01/product/2
```
<img width="974" alt="image" src="https://github.com/user-attachments/assets/8aa90232-70a0-4b05-a730-8c059c506db2" />


https://github.com/vinsguru/webflux-patterns
