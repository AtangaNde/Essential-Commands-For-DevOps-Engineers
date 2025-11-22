1. helm version – Check Helm version

2. helm repo add stable 
https://charts.helm.sh/stable – Add Helm
repository

3. helm repo update – Update Helm repositories

4. helm search repo nginx – Search for a Helm chart

5. helm install myapp stable/nginx – Install a Helm
chart

6. helm upgrade myapp stable/nginx – Upgrade a Helm
release

7. helm rollback myapp 1 – Rollback release to a
previous version

8. helm uninstall myapp – Uninstall a Helm release

9. helm list – List all installed Helm releases

10. helm status myapp – Show the status of a Helm
release

11. helm get values myapp – Show values used in a
Helm release

12. helm get manifest myapp – Show Kubernetes
manifests of a release

13. helm template myapp stable/nginx – Render chart
templates locally

14. helm lint mychart/ – Validate Helm chart syntax

15. helm package mychart/ – Package a Helm chart

16. helm repo remove stable – Remove a Helm
repository

17. helm dependency update mychart/ – Update chart
dependencies

18. helm dependency build mychart/ – Build chart
dependencies

19. helm history myapp – Show the history of a Helm
release

20. helm create mychart – Create a new Helm chart

21. helm pull stable/nginx – Download a chart

22. helm plugin list – List installed Helm plugins

23. helm env – Show Helm environment variables

24. helm show values stable/nginx – Show default
values of a chart

25. helm upgrade --install myapp stable/nginx –
Install or upgrade release
