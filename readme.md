## Start the app

```
mvn clean install -DskipTests && mvn spring-boot:run
```


## Request keys from keystore
```
curl -i http://localhost:8080/k_jwks
```

