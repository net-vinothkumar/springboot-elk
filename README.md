# Springboot-ELK
Spring Boot application sending logs to "Elastic Search Logstash Kibana" demo

# Why ELK ?
With use of microservices, we have been able to overcome many traditional problems and it allow us to create stable distributed applications with desired control on the code, team size, maintenance, release cycle, cloud ennoblement , automation, etc. But it has also introduced few challenges in other areas e.g. "distributed log management" and ability to view logs of full transaction distributed among many services and distributed debugging in general.

Actually the challenge is that microservices are isolated among themselves and they does not share common database and log files. As the number of microservice increases and we enable cloud deployment with automated continuous integration tools, it is very much necessary to have some provision of debugging the components when we have any problem.

Thanks to the open source. We already have bundle of tools which can do the magic if used properly together. One such popular set of tools are Elastic Search, Logstash and Kibana – together referred as ELK stack. They are used for searching, analyzing, and visualizing log data in a real time.


