/home/alex/code_stuff/java/prometheus/kafka_exporter-1.6.0.linux-amd64/kafka_exporter   --kafka.server=192.168.88.169:9292 --kafka.server=192.168.88.168:9293 --kafka.server=192.168.88.168:9294   --kafka.version=3.9.0   --tls.enabled   --tls.ca-file=/home/alex/code_stuff/java/kafka_2.13-3.9.0/config/certs/take_5/ssl/prometheus/ca.pem   --tls.cert-file=/home/alex/code_stuff/java/kafka_2.13-3.9.0/config/certs/take_5/ssl/prometheus/kafka-client.pem   --tls.key-file=/home/alex/code_stuff/java/kafka_2.13-3.9.0/config/certs/take_5/ssl/prometheus/kafka-client-key.pem   --web.listen-address=:9091

./prometheus-3.3.0.linux-amd64/prometheus --config.file=prometheus.yaml


