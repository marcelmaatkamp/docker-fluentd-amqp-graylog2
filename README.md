# Fluentd inputs via RabbitMQ into Graylog2

## Toplogy

 host:[syslog=5140|fluentd=24224] -> rabbitmq -> graylog:9000 ( -> elasticsearch )
