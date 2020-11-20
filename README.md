# spring-batch-sample

Partire da Spring Batch jdbc starter

- https://spring.io/guides/gs/batch-processing/
- https://docs.spring.io/spring-batch/docs/current/reference/html/common-patterns.html
- Scaling and Parallel Processing
 https://docs.spring.io/spring-batch/docs/current/reference/html/scalability.html
- Spring boot 
https://spring.io/guides/gs/relational-data-access/

Distribution

sia Uber jar con tutto che jar singoli, senza differenze per ambiente. Magari tenere config.yml fuori dalla distribuzione

Step Scope

- ItemReaders and ItemWriters
https://docs.spring.io/spring-batch/docs/current/reference/html/readersAndWriters.html
- How to handle stateful item reader in SpringBatch - Stack Overflow
https://stackoverflow.com/questions/37007823/how-to-handle-stateful-item-reader-in-springbatch
- How Does Spring Batch Step Scope Work - Stack Overflow
(specifying a spring batch component being StepScope means that Spring Batch will use the spring container to instantiate a new instance of that component for each step execution)
https://stackoverflow.com/questions/38780796/how-does-spring-batch-step-scope-work

Gestione log

In config Path, archiviazione, level

Gestire Datasource Dinamico

https://stackoverflow.com/questions/28821521/configure-datasource-programmatically-in-spring-boot

https://stackoverflow.com/questions/42087518/dynamic-datasource-as-second-datasource-in-spring-boot-hibernate