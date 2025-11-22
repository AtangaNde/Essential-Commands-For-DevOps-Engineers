1. docker --version – Check Docker version

2. docker ps – List running containers

3. docker ps -a – List all containers

4. docker images – List all images

5. docker run -d -p 8080:80 image_name – Run a
container

6. docker exec -it container_id bash – Access a
running container

7. docker stop container_id – Stop a container

8. docker rm container_id – Remove a container

9. docker rmi image_id – Remove an image

10. docker-compose up -d – Start containers using
Docker Compose

11. docker-compose down – Stop and remove all
containers

12. docker build -t my_image . – Build an image from
a Dockerfile

13. docker pull image_name – Download an image from
Docker Hub

14. docker push myrepo/image_name – Push image to
registry

15. docker logs container_id – View container logs

16. docker inspect container_id – Get container
details

17. docker network ls – List Docker networks

18. docker network inspect network_name – Inspect
network details

19. docker volume ls – List Docker volumes

20. docker volume inspect volume_name – Inspect
volume details

21. docker system prune -a – Clean up unused
containers, images, and networks

22. docker login – Authenticate with Docker Hub

23. docker logout – Logout from Docker Hub

24. docker stats – Show live container resource usage

25. docker top container_id – Show running processes
inside a container

26. docker tag image_id new_repo:new_tag – Tag an
image

27. docker restart container_id – Restart a container

28. docker update --restart=always container_id – Set
restart policy

29. docker rename old_name new_name – Rename a
container

30. docker wait container_id – Wait for a container
to exit

31. docker events – Show real-time events

32. docker history image_name – Show image history

33. docker cp container_id:/path/to/file . – Copy
file from container

34. docker diff container_id – Show container file
changes

35. docker pause container_id – Pause a running
container

36. docker unpause container_id – Resume a paused
container

37. docker info – Show Docker system information

38. docker search image_name – Search for an image on
Docker Hub

39. docker run --rm image_name – Run a container and
remove after exit

40. docker network create my_network – Create a
custom Docker network

41. docker network connect my_network container_id –
Connect container to a network

42. docker network disconnect my_network container_id
– Disconnect container from a network

43. docker-compose build – Build services defined in
docker-compose.yml

44. docker-compose ps – List services in a Docker
Compose setup

45. docker-compose restart – Restart all services in
Compose

46. docker-compose logs -f – Tail logs for all
services

47. docker-compose exec service_name bash – Run
command inside a service container

48. docker-compose scale service=3 – Scale a service
to 3 instances

49. docker-compose stop – Stop all services without
removing containers

50. docker-compose config – Validate Docker Compose
config
