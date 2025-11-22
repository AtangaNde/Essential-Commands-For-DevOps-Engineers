1. kubectl get nodes – List nodes in the cluster

2. kubectl get pods – List pods

3. kubectl describe pod pod_name – Show pod details

4. kubectl logs pod_name – Show pod logs

5. kubectl exec -it pod_name -- bash – Access a
running pod

6. kubectl apply -f file.yaml – Apply a YAML file

7. kubectl delete pod pod_name – Delete a pod

8. kubectl get svc – List services

9. kubectl get deployments – List deployments

10. kubectl scale deployment my-deploy --replicas=5 –
Scale deployment

11. kubectl rollout status deployment my-deploy –
Check rollout status

12. kubectl get configmaps – List ConfigMaps

13. kubectl get secrets – List Secrets

14. kubectl create configmap my-config
--from-file=config.txt – Create ConfigMap
165. kubectl create secret generic my-secret
--from-literal=key=value – Create Secret

16. kubectl port-forward pod/my-pod 8080:80 – Forward
port

17. kubectl delete svc my-service – Delete a service

18. kubectl expose deployment my-deploy
--type=NodePort --port=80 – Expose deployment

19. kubectl get ingress – List Ingress resources

20. kubectl describe ingress my-ingress – Show
Ingress details

21. kubectl get namespaces – List namespaces

22. kubectl create namespace my-namespace – Create a
namespace
173. kubectl delete namespace my-namespace – Delete a
namespace

24. kubectl config view – View kubeconfig settings

25. kubectl get events – Show cluster events

26. kubectl drain node_name – Drain a node for
maintenance

27. kubectl uncordon node_name – Mark node as
schedulable

28. kubectl taint nodes node_name 
key=value:NoSchedule – Taint a node

29. kubectl edit deployment my-deploy – Edit
deployment config

30. kubectl rollout undo deployment my-deploy –
Rollback deployment

31. kubectl set image deployment/my-deploy 
container-name=myimage:v2 – Update container
image

32. kubectl autoscale deployment my-deploy --min=2
--max=5 --cpu-percent=80 – Autoscale deployment

33. kubectl get hpa – Show Horizontal Pod Autoscaler

34. kubectl cordon node_name – Mark node as
unschedulable

35. kubectl delete -f resource.yaml – Delete a
resource using YAML

36. kubectl top nodes – Show node resource usage

37. kubectl top pods – Show pod resource usage

38. kubectl get pv – List PersistentVolumes

39. kubectl get pvc – List PersistentVolumeClaims

40. kubectl logs -f pod_name – Stream logs from a pod

41. kubectl exec -it pod_name -- sh – Access a pod
using sh shell

42. kubectl delete pod --grace-period=0 --force
pod_name – Force delete pod

43. kubectl getall – List all resources

44. kubectl getroles – List roles

45. kubectl getrolebindings – List role bindings

46. kubectl getclusterroles – List cluster roles

47. kubectl get clusterrolebindings – List cluster
role bindings

48. kubectl get networkpolicy – List network policies

49. kubectl delete node node_name – Delete a node

50. kubectl run nginx --image=nginx --restart=Never –
Run a single pod
