## CodeScene

This is my private CodeScene setup

### Start CodeScene instance

```shell
docker-compose up -d
```

### Generate SSH key

```shell
docker-compose exec -u codescene codescene ssh-keygen
```

### Display SSH key

```shell
docker-compose exec -u codescene codescene ssh-keygen -y
```

### Register SSH key with VSC
Add the SSH key to a user on your repository provider with read access to your repositories.

### Run CodeScene
Go to the CodeScene URL (https://localhost:3003), validate and login using your license credentials, and create projects using the Specify Remotes option.