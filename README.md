# Spring Security Samples

## Resources

- [Spring Security Reference](http://docs.spring.io/spring-security/site/docs/current/reference/html/)
- [Rob Winch - Github](https://github.com/rwinch) - Spring Security & LDAP project lead

## General Configuration

### Dependencies

Minimal set of dependencies are:

- spring-security-web
- spring-security-config

#### Maven dependencies

```xml
<dependency>
	<groupId>org.springframework.security</groupId>
	<artifactId>spring-security-web</artifactId>
	<version>${spring-security.version}</version>
</dependency>
<dependency>
	<groupId>org.springframework.security</groupId>
	<artifactId>spring-security-config</artifactId>
	<version>${spring-security.version}</version>
</dependency>
```