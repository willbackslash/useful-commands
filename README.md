# useful-commands
Repo for these commands that you usually use but that you forget easily

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
