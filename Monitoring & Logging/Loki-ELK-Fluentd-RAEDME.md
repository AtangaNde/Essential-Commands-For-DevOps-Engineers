1. loki -config.file=loki-config.yml – Start Loki
with config file

2. curl -X GET
http://localhost:3100/loki/api/v1/labels – Get 
available labels

3. curl -X GET 
'http://localhost:3100/loki/api/v1/query?query={app
="nginx"}' – Query logs
ELK Stack (Elasticsearch, Logstash, Kibana)

4. curl -X GET "localhost:9200/_cat/indices?v" –
List Elasticsearch indices

5. curl -X POST "localhost:9200/logs/_doc/" -H 
"Content-Type: application/json" -d
'{"message": "hello world"}' – Insert a log 
entry

6. curl -X GET "localhost:9200/logs/_search" –
Search logs

7. systemctl start logstash – Start Logstash

8. systemctl restart kibana – Restart Kibana
Fluentd (Log Forwarding)

9. fluentd --config fluentd.conf – Start Fluentd
with a specific config

10. fluentd --dry-run --config fluentd.conf –
Validate Fluentd config
