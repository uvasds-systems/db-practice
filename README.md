# db-practice

To work with MySQL directly, you can run one locally or within Codespaces with the following command:

```
docker run -e MYSQL_ROOT_PASSWORD=abc123 -d mysql
```

That will run the database container. Next, find the ID of the running container with this command:
```
docker ps
```
Once you know the ID of the container, open a bash terminal into it:
```
docker exec -it b7c5d3 bash
```
