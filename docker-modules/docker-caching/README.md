## TL;DR:
1. Keep final image as small as possible : by using Multi Stage Build 
2. Separate codes changes from dependencies : by  Docker Layers Cache
3. Reduce build-time : by using BuildKit to cache both runtime's dependencies and plugin/module dependencies
4. Force update to fetch plugins/submodules when updated : by separating project into layers and using Maven incremental builds

## Relevant Articles:

- [Caching Maven Dependencies with Docker](https://www.baeldung.com/ops/docker-cache-maven-dependencies)

- [Building an Application with Spring Boot](https://spring.io/guides/gs/spring-boot/)
