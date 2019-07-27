# Project
Refactor Application Into Microservices

## Description
*   Split apart an application that was built in a traditional monolithic architecture into individual functionalities (microservices).  
*   In between main application and services we added a service registry that will know where to find the services in the infrastructure. 
*   The service registry will also provide some load balancing.
*   I added a communication layer to the main application that provides some resilience against outages.
*   Additional layer of abstraction is added by using a queue to send feedbacks communication channel instead of posting data directly to the respective services.

 ### Author
 Chris Campbell
