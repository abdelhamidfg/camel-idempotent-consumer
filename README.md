# camel-idempotent-consumer

1. Deploy AMQ Streams operator on openshift
2. Create Kafka broker
3. Create Kafka topics  
    orders-duplicate-topic ,orders-filtered-topic  
4. Configure  kafka broker url in kafka.properties   
5. Deploy camel k operator on openshift
6. Deploy Producer Route  
  kamel run OrderProducer.java 
7. Deploy Idempotent Consumer Route  
   kamel run IdempotentOrderConsumer.java 




