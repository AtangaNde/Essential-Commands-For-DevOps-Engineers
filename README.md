# Essential-Commands-For-DevOps-Engineers

## LINUX COMMANDS

1.uname -a – Show system information

2.uptime – Show system uptime

3.hostname – Show hostname

4.whoami – Show current user

5.ls -lah – List directory contents with permissions

6.pwd – Show current directory

7.cd /path – Change directory

8.mkdir -p /path – Create a directory (with parent

if needed)

9.rm -rf /path – Remove directory recursively

10. cp -r source target – Copy files/directories
recursively

11. mv oldname newname – Move/Rename file

12. ps aux – Show running processes

13. top – Show real-time system performance

14. kill -9 PID – Kill a process forcefully

15. pkill -f process_name – Kill process by name

16. df -h – Show disk space usage

17. du -sh /path – Show directory size

18. netstat -tulnp – Show listening ports

19. ss -tulnp – Show listening ports (alternative)

20. who – Show logged-in users

21. adduser username – Create a new user

22. passwd username – Change user password

23. usermod -aG group user – Add user to a group

24. grep "text" file.txt – Search for a string in a
file

25. find /path -name "*.log" – Find files matching
pattern

26. chmod 755 file.sh – Change file permissions

27. chown user:group file – Change file owner

28. tar -czf archive.tar.gz directory/ – Compress
files

29. tar -xzf archive.tar.gz – Extract compressed file

30. cat file.txt – View file contents

31. tail -f /var/log/syslog – View real-time log
updates

32. echo "text" >> file.txt – Append text to file

33. history – Show command history

34. clear – Clear terminal screen

35. alias ll='ls -lah' – Create an alias

36. df -Th – Show file system disk space

37. wc -l file.txt – Count number of lines in a file

38. cut -d':' -f1 /etc/passwd – Extract first column
from file

39. awk '{print $1}' file.txt – Print first column of
Text

40. sed -i 's/old/new/g' file.txt – Replace text in a
file

41. crontab -e – Edit cron jobs

42. cron -l – List scheduled cron jobs

43. rsync -av source/ target/ – Sync files

44. scp user@host:/path/to/file . – Secure copy file

45. ssh user@host – SSH into a server

46. exit – Logout from shell

47. uptime – Show system uptime

48. free -m – Show memory usage

49. top – Show system performance

50. vmstat – Show CPU/memory status

## GIT COMMANDS 

52. git init – Initialize a git repository

53. git clone repo_url – Clone a repository

54. git status – Show changes

55. git add . – Stage all changes

56. git commit -m "msg" – Commit changes

57. git push origin branch – Push changes

58. git pull origin branch – Pull latest changes

59. git checkout branch – Switch branch

60. git branch -a – List all branches

61. git merge branch – Merge branch into current
branch

62. git log --oneline – Show commit history

63. git diff – Show changes

64. git stash – Stash changes

65. git stash pop – Apply stashed changes

66. git reset --hard HEAD~1 – Reset last commit

67. git revert commit_id – Revert commit

68. git tag -a v1.0 -m "Version 1.0" – Create tag

69. git push --tags – Push tags

70. git rm file – Remove a file from git

71. git clean -fd – Remove untracked files

72. git config --global user.name "Your Name" – Set
global username

73. git config --global user.email "you@example.com"
– Set global email

74. git show commit_id – Show commit details

75. git blame file.txt – Show changes by line

76. git remote -v – Show remote repositories

77. git remote add origin URL – Add remote repo

78. git rebase branch – Rebase branch

79. git cherry-pick commit_id – Pick specific commit

80. git fetch – Fetch remote changes

81. git log --graph – Show graphical commit log

82. git branch -d branch_name – Delete branch

83. git pull --rebase – Rebase while pulling

84. git push --force – Force push changes

85. git reflog – Show reflog

86. git diff HEAD~1 – Show last commit changes

87. git apply patch.diff – Apply patch

88. git reset --soft HEAD~1 – Soft reset

89. git archive --format=tar.gz HEAD > archive.tar.gz
– Archive repo

90. git grep "search_term" – Search for text

91. git bisect start – Start binary search

92. git ls-files – List tracked files

93. git update-index --assume-unchanged file – Ignore
file temporarily

94. git push origin --delete branch_name – Delete
remote branch

95. git pull --all – Fetch all branches

96. git submodule add URL path – Add a submodule

97. git submodule update --init --recursive – Update
submodules

98. git commit --amend -m "Updated commit message" –
Amend commit

99. git fetch --prune – Remove deleted remote
branches

100. git push --mirror destination_url – Mirror
repository

101. git worktree add ../branch_name branch_name –
Work with multiple branches

## DOCKER COMMANDS 

101. docker --version – Check Docker version

102. docker ps – List running containers

103. docker ps -a – List all containers

104. docker images – List all images

105. docker run -d -p 8080:80 image_name – Run a
container

106. docker exec -it container_id bash – Access a
running container

107. docker stop container_id – Stop a container

108. docker rm container_id – Remove a container

109. docker rmi image_id – Remove an image

110. docker-compose up -d – Start containers using
Docker Compose

111. docker-compose down – Stop and remove all
containers

112. docker build -t my_image . – Build an image from
a Dockerfile

113. docker pull image_name – Download an image from
Docker Hub

114. docker push myrepo/image_name – Push image to
registry

115. docker logs container_id – View container logs

116. docker inspect container_id – Get container
details

117. docker network ls – List Docker networks

118. docker network inspect network_name – Inspect
network details

119. docker volume ls – List Docker volumes

120. docker volume inspect volume_name – Inspect
volume details

121. docker system prune -a – Clean up unused
containers, images, and networks

122. docker login – Authenticate with Docker Hub

123. docker logout – Logout from Docker Hub

124. docker stats – Show live container resource usage

125. docker top container_id – Show running processes
inside a container

126. docker tag image_id new_repo:new_tag – Tag an
image

127. docker restart container_id – Restart a container

128. docker update --restart=always container_id – Set
restart policy

129. docker rename old_name new_name – Rename a
container

130. docker wait container_id – Wait for a container
to exit

131. docker events – Show real-time events

132. docker history image_name – Show image history

133. docker cp container_id:/path/to/file . – Copy
file from container

134. docker diff container_id – Show container file
changes

135. docker pause container_id – Pause a running
container

136. docker unpause container_id – Resume a paused
container

137. docker info – Show Docker system information

138. docker search image_name – Search for an image on
Docker Hub

139. docker run --rm image_name – Run a container and
remove after exit

140. docker network create my_network – Create a
custom Docker network

141. docker network connect my_network container_id –
Connect container to a network

142. docker network disconnect my_network container_id
– Disconnect container from a network

143. docker-compose build – Build services defined in
docker-compose.yml

144. docker-compose ps – List services in a Docker
Compose setup

145. docker-compose restart – Restart all services in
Compose

146. docker-compose logs -f – Tail logs for all
services

147. docker-compose exec service_name bash – Run
command inside a service container

148. docker-compose scale service=3 – Scale a service
to 3 instances

149. docker-compose stop – Stop all services without
removing containers

150. docker-compose config – Validate Docker Compose
config

## KUBERNETES COMMANDS

151. kubectl get nodes – List nodes in the cluster

152. kubectl get pods – List pods

153. kubectl describe pod pod_name – Show pod details

154. kubectl logs pod_name – Show pod logs

155. kubectl exec -it pod_name -- bash – Access a
running pod

156. kubectl apply -f file.yaml – Apply a YAML file

157. kubectl delete pod pod_name – Delete a pod

158. kubectl get svc – List services

159. kubectl get deployments – List deployments

160. kubectl scale deployment my-deploy --replicas=5 –
Scale deployment

161. kubectl rollout status deployment my-deploy –
Check rollout status

162. kubectl get configmaps – List ConfigMaps

163. kubectl get secrets – List Secrets

164. kubectl create configmap my-config
--from-file=config.txt – Create ConfigMap

165. kubectl create secret generic my-secret
--from-literal=key=value – Create Secret

166. kubectl port-forward pod/my-pod 8080:80 – Forward
port

167. kubectl delete svc my-service – Delete a service

168. kubectl expose deployment my-deploy
--type=NodePort --port=80 – Expose deployment

169. kubectl get ingress – List Ingress resources

170. kubectl describe ingress my-ingress – Show
Ingress details

171. kubectl get namespaces – List namespaces

172. kubectl create namespace my-namespace – Create a
namespace

173. kubectl delete namespace my-namespace – Delete a
namespace

174. kubectl config view – View kubeconfig settings

175. kubectl get events – Show cluster events

176. kubectl drain node_name – Drain a node for
maintenance

177. kubectl uncordon node_name – Mark node as
schedulable

178. kubectl taint nodes node_name 
key=value:NoSchedule – Taint a node

179. kubectl edit deployment my-deploy – Edit
deployment config

180. kubectl rollout undo deployment my-deploy –
Rollback deployment

181. kubectl set image deployment/my-deploy 
container-name=myimage:v2 – Update container
image

182. kubectl autoscale deployment my-deploy --min=2
--max=5 --cpu-percent=80 – Autoscale deployment

183. kubectl get hpa – Show Horizontal Pod Autoscaler

184. kubectl cordon node_name – Mark node as
unschedulable

185. kubectl delete -f resource.yaml – Delete a
resource using YAML

186. kubectl top nodes – Show node resource usage

187. kubectl top pods – Show pod resource usage

188. kubectl get pv – List PersistentVolumes

189. kubectl get pvc – List PersistentVolumeClaims

190. kubectl logs -f pod_name – Stream logs from a pod

191. kubectl exec -it pod_name -- sh – Access a pod
using sh shell

192. kubectl delete pod --grace-period=0 --force
pod_name – Force delete pod

193. kubectl getall – List all resources

194. kubectl getroles – List roles

195. kubectl getrolebindings – List role bindings

196. kubectl getclusterroles – List cluster roles

197. kubectl get clusterrolebindings – List cluster
role bindings

198. kubectl get networkpolicy – List network policies

199. kubectl delete node node_name – Delete a node

200. kubectl run nginx --image=nginx --restart=Never –
Run a single pod

## TERRAFORM COMMANDS

201. terraform --version – Check Terraform version

202. terraform init – Initialize Terraform working
directory

203. terraform plan – Show execution plan

204. terraform apply -auto-approve – Apply
configuration

205. terraform destroy -auto-approve – Destroy
infrastructure

206. terraform show – Show Terraform state

207. terraform validate – Validate Terraform
configuration

208. terraform fmt – Format Terraform code

209. terraform providers – List providers used

210. terraform state list – Show managed resources

211. terraform state show resource_name – Show
specific resource details

212. terraform state rm resource_name – Remove
resource from state

213. terraform taint resource_name – Mark resource for
recreation

214. terraform untaint resource_name – Remove taint
from resource

215. terraform import resource_type.name id – Import
existing infrastructure

216. terraform refresh – Refresh state file

217. terraform graph – Generate dependency graph

218. terraform workspace list – List available
workspaces

219. terraform workspace select workspace_name –
Switch workspace

220. terraform workspace new workspace_name – Create
new workspace

221. terraform state mv old_resource new_resource –
Rename resource

222. terraform output – Show Terraform outputs

223. terraform output output_name – Get specific
output value

224. terraform apply -target=resource_name – Apply
specific resource

225. terraform console – Open interactive Terraform
shell

226. terraform debug – Enable debugging logs

227. terraform version – Show installed Terraform
version

228. terraform plan -var="instance_type=t2.micro" –
Pass variable via CLI

229. terraform apply -var-file="vars.tfvars" – Apply
using variable file

230. terraform apply -auto-approve – Skip manual
approval

231. terraform workspace delete workspace_name –
Delete workspace

232. terraform plan -detailed-exitcode – Get exit
codes for changes

233. terraform force-unlock LOCK_ID – Unlock Terraform
state

234. terraform state push – Manually push state file

235. terraform state pull – Download current state
file

236. terraform output -json – Get output in JSON
format

237. terraform fmt -recursive – Format Terraform in
subdirectories

238. terraform destroy -target=resource_name – Destroy
specific resource

239. terraform show -json – Show JSON output

240. terraform validate -no-color – Validate without
Colors

241. terraform workspace select default – Switch to
default workspace

242. terraform plan -var 'region=us-east-1' – Pass a
variable inline

243. terraform apply -refresh-only – Only refresh
state, do not modify

244. terraform state replace-provider old new –
Replace provider

245. terraform plan -out=tfplan – Save plan output

246. terraform apply tfplan – Apply saved plan

247. terraform version -json – Output Terraform
version in JSON

248. terraform workspace show – Show current workspace

249. terraform plan -var-file=config.tfvars – Use a
variable file

250. terraform output -state=terraform.tfstate – Show
output from a specific state file
