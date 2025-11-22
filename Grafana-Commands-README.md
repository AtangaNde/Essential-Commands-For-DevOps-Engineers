1. grafana-server --version – Check Grafana version

2. systemctl start grafana-server – Start Grafana
service

3. systemctl stop grafana-server – Stop Grafana
service

4. systemctl restart grafana-server – Restart
Grafana

5. systemctl status grafana-server – Check Grafana
status

6. grafana-cli plugins list – List installed plugins

7. grafana-cli plugins install grafana-clock-panel –
Install a Grafana plugin

8. grafana-cli plugins update-all – Update all
plugins

9. grafana-cli admin reset-admin-password
newpassword – Reset admin password

10. curl http://localhost:3000/api/health – Check
Grafana health

11. curl -u admin:admin 
http://localhost:3000/api/dashboards/home –
Get home dashboard

12. grafana-cli plugins remove plugin-name – Remove a
plugin

13. grafana-cli admin reset-admin-password newpass –
Reset admin password

14. grafana-server -config /etc/grafana/grafana.ini –
Start with custom config

15. curl -X GET http://localhost:3000/api/dashboards
– List dashboards

16. curl -X POST
http://localhost:3000/api/dashboards/db -d 
'@dashboard.json' – Create dashboard

17. journalctl -u grafana-server --no-pager – Check
logs

18. grafana-cli plugins install
grafana-simple-json-datasource – Install JSON data 
source

19. grafana-cli plugins update – Update Grafana
plugins

20. systemctl enable grafana-server – Enable Grafana
on startup

21. grafana-cli plugins update-all – Update all
plugins

22. grafana-cli server restart – Restart Grafana

23. grafana-cli admin reset-admin-password
mynewpassword – Reset password

24. curl http://localhost:3000/api/org – Get
organization details

25. grafana-server --homepath /var/lib/grafana – Run
Grafana with a specific path
