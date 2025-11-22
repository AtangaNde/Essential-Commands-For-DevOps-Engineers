1. prometheus --version – Check Prometheus version

2. promtool check config prometheus.yml – Validate
Prometheus configuration

3. prometheus --config.file=prometheus.yml – Start
Prometheus

4. prometheus --storage.tsdb.path=data
storage path

5. prometheus --web.listen-address=:9090 – Start
Prometheus on a specific port

                                                                                                                            6. curl http://localhost:9090/api/v1/targets – Check
active Prometheus targets

6. curl http://localhost:9090/api/v1/status/config –
Fetch Prometheus config

7. curl http://localhost:9090/api/v1/query?query=up
– Run an instant query

8. prometheus --query.lookback-delta=5m – Adjust
query range

9. prometheus --storage.tsdb.retention.time=15d –
ometheus Comma
/ – Define
Set data retention

10. prometheus --web.enable-lifecycle – Enable reload
API

11. curl -X POST http://localhost:9090/-/reload –
Reload configuration

12. systemctl restart prometheus – Restart Prometheus
service

13. journalctl -u prometheus --no-pager – Check
Prometheus logs

14. promtool check rules rules.yml – Validate
recording rules

15. prometheus --storage.tsdb.max-block-duration=2h –
Adjust block duration

16. prometheus --storage.tsdb.no-lockfile – Disable
lockfile

17. prometheus --enable-feature=remote-write-receiver
– Enable remote write

18. prometheus --web.enable-admin-api – Enable admin
API

19. promtool query instant http://localhost:9090 "up"
– Query using promtool

20. promtool tsdb analyze data/ – Analyze TSDB
database

21. curl http://localhost:9090/api/v1/rules – Show
alerting rules

22. prometheus --log.level=debug – Start Prometheus
with debug logs

23. promtool check-metrics metrics.prom – Validate
metrics file

24. prometheus --config.file=prometheus.yml
--web.console.templates=console/ – Load custom web 
templates
