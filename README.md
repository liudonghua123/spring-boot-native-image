# spring-boot-native-image

## What is it

This is a simple Spring-boot web app which integrated with [Graalvm](https://www.graalvm.org/)'s [native-image](https://www.graalvm.org/reference-manual/native-image/), only minimal tools are included. All the three desktop prebuilt binaries are build and deployed using github actions. Inspired by https://github.com/recursivecodes/simple-socket-fn-logger.

The [native-image](https://www.graalvm.org/reference-manual/native-image/) is done using [`native-maven-plugin`](https://graalvm.github.io/native-build-tools/latest/index.html) plugin.

## How to make a platform-specific native-image binary

`mvn package -P native`

## Resources

- https://docs.spring.io/spring-native/docs/current/reference/htmlsingle/
- https://github.com/recursivecodes/simple-socket-fn-logger
- https://github.com/spring-projects-experimental/spring-native
- https://github.com/hantsy/spring-native-example
- https://www.graalvm.org/reference-manual/native-image/
- https://github.com/jonashackt/spring-boot-graalvm


## LICENSE

MIT License

Copyright (c) 2021 liudonghua