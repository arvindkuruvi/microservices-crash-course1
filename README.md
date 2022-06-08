# microservices-crash-course1

For eureka server
***************************
eureka:
  client:
    registerWithEureka: false
    fetchRegistry: false
    service-url:
      defaultZone: http://locslhost:8778/eureka
  instancs:
    hostname: localhost
    
    
    
 
For eureka clients
***************************
    
eureka:
  client:
    service-url:
      defaultZone: http://locslhost:8778/eureka
  instancs:
    hostname: localhost
