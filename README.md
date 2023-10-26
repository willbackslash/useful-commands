# useful-commands
Repo for these commands that you usually use but that you forget easily

## Install docker on ubuntu
https://www.linode.com/docs/applications/containers/install-docker-ce-ubuntu-1804/

---
## Common Docker containers
### Postgres
```docker run -d -p 5432:5432 --name postgres -e POSTGRES_PASSWORD=password postgres```

### MySQL
```docker run -d -p 3306:3306 --name mysql -e MYSQL_ROOT_PASSWORD=password -d mysql:tag```

---
## Unix
### Kill process running under certain port
```sudo kill $(sudo lsof -t -i:8000)``` OR
```sudo fuser -k -n tcp 8000 ```

### Development
#### Exporting variables from .env file
```console
set -a && source .env
```

---
## Java
### Run SonarQube analysis
```mvn clean verify sonar:sonar```
### Fix Lint Errors with Coveo
```mvn com.coveo:fmt-maven-plugin:format```

---
## Go
### Init a go mod
```go mod init```
### Install a dependency (ex: gokit/kit)
```go get github.com/go-kit/kit```

---
## GIT
### Remove all local branches excluding master
```git branch | grep -v "master" | xargs git branch -D ```

# Useful websites
Icons: https://yesicon.app

