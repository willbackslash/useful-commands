# useful-commands
Repo for these commands that you usually use but that you forget easily

---
## Common Docker containers
### Postgres
```docker run -d -p 5432:5432 --name postgres -e POSTGRES_PASSWORD=password postgres```

---
## Unix
### Kill process running under certain port
```sudo kill $(sudo lsof -t -i:8000)``` OR
```sudo fuser -k -n tcp 8000 ```

---
## Java
### Run SonarQube analysis
```mvn clean verify sonar:sonar```
### Fix Lint Errors with Coveo
```mvn com.coveo:fmt-maven-plugin:format```
