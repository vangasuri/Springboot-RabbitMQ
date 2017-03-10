# Springboot-RabbitMQ
 Install ERLang process. This installation is required for RabbitMQ to work. (http://www.erlang.org/downloads)
 Download and install the Rabbit MQ version.(https://www.rabbitmq.com/)
 Run this command "rabbitmq-plugins enable rabbitmq_management" in Rabbit MQ install directory /sbin. This will enables the management plugins.
you can control RabbitMQ server from your registry. (run services.msc)
http://localhost:15672/#  guest/guest is the default credentials for RabbitMQ management console.
References : https://spring.io/guides/gs/messaging-rabbitmq/
Run : mvn spring-boot:run
