# config-service

Config Service for Polar Bookshop that use Spring Cloud Config Server.

## Build and Run locally

```bash
./gradlew build -i
```

```
./gradlew bootRun
```

## Vulnerability Scan

We will use [grype](https://github.com/anchore/grype) as our vulnerability scanner for CI and locally.

```bash
grype . --name config-service
```

## References

* Created
  using [Spring Inilializr](https://start.spring.io/#!type=gradle-project&language=java&platformVersion=3.5.5&packaging=jar&jvmVersion=24&groupId=com.github.polar&artifactId=config-service&name=config-service&description=Config%20Service%20for%20Polar%20Bookshop%20&packageName=com.github.polar.configservice&dependencies=cloud-config-server)

