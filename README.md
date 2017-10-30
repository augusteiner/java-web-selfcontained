# Self-contained webapp with tomcat

## References

- [How to create microservices with tomcat](https://www.c2b2.co.uk/middleware-blog/how-to-create-microservices-with-tomcat.php);

## Included (incomplete/untested list)

- jsp
- el
- tomcat
- servlet api 3.0

## Building

```bash
./mvnw package
```

## Running

```bash
env TOMCAT_PORT=$PORT java -jar target/standalone.jar
```

### or

```bash
chmod u+x target/standalone.jar
env TOMCAT_PORT=$PORT target/standalone.jar
```
