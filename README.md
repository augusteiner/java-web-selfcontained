# Self-contained webapp with tomcat7

## Included (incomplete/untested list)

- jsp
- el
- tomcat7
- servlet api 3.0

## Building

```bash
./mvnw package
```

## Running

```bash
java -jar target/standalone.jar --httpPort=$PORT
```

### or

```bash
chmod u+x target/standalone.jar
target/standalone.jar --httpPort=$PORT
```
