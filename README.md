[![Build Status](https://travis-ci.org/netshoes/spring-cloud-sleuth-amqp.svg?branch=master)](https://travis-ci.org/netshoes/spring-cloud-sleuth-amqp)
[![Coverage Status](https://coveralls.io/repos/netshoes/spring-cloud-sleuth-amqp/badge.svg?branch=master&service=github)](https://coveralls.io/github/netshoes/spring-cloud-sleuth-amqp?branch=master)
[![License Apache2](https://img.shields.io/hexpm/l/plug.svg)](http://www.apache.org/licenses/LICENSE-2.0)

# Why?
The project spring-cloud-sleuth does not provided a instrumentation for spring-rabbit. In this project we implement this instrumentation.

# Compatibility
| spring-cloud-sleuth-amqp          | spring-cloud-sleuth | spring-rabbit |
| --------------------------------- | ------------------- | ------------- |
| 0.8                               | 1.2.1.RELEASE       | 1.7.3.RELEASE |

# Usage
Add the following dependency to project:
```
<dependency>
  <groupId>com.netshoes</groupId>
  <artifactId>spring-cloud-sleuth-amqp</artifactId>
  <version>0.8</version>
</dependency>
```

# Contributing
Pull request are welcome. This project is not supported by Spring Framework Team and has its own rules:
* Use [google-java-format](https://github.com/google/google-java-format) to format your code.