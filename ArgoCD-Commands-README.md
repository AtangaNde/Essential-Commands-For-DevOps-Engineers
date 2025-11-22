1. argocd login my-argocd.com – Login to ArgoCD

2. argocd app list – List all ArgoCD applications

3. argocd version – Show ArgoCD CLI version

3. argocd app get my-app – Show details of an app

4. argocd app sync my-app – Sync an application

5. argocd app delete my-app – Delete an application

6. argocd app rollback my-app 1 – Rollback an
application

7. argocd app history my-app – Show deployment
history

8. argocd app create my-app --repo
https://github.com/user/repo.git --path app – 
Create an application

9. argocd app update my-app --sync-policy automated
– Enable auto-sync

10. argocd app set my-app --dest-server 
https://k8s-cluster – Set destination server

11. argocd app unset my-app --dest-server – Unset
destination server

12. argocd repo list – List connected repositories

13. argocd repo add https://github.com/user/repo.git
– Add a repository

14. argocd cluster list – List managed clusters

15. argocd cluster add my-cluster – Add a new cluster

16. argocd login my-argocd.com --username admin
--password pass – Login with credentials

17. argocd app diff my-app – Show differences in
application

18. argocd proj list – List ArgoCD projects

19. argocd proj create my-project – Create a project

20. argocd proj delete my-project – Delete a project

21. argocd settings list – Show ArgoCD settings

22. argocd account list – List user accounts

23. argocd logout – Logout from ArgoCD

24. argocd help – Show help for ArgoCD CLI
