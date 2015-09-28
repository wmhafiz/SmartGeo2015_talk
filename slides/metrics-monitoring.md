##  Metrics Monitoring

- Monitors the JVM, app server, REST endpoints, Spring beans, cache etc

```java
    @RequestMapping(value = "/users",
        method = RequestMethod.GET,
        produces = MediaType.APPLICATION_JSON_VALUE)
    @Timed
    public List<User> getAll() {
        log.debug("REST request to get all Users");
        return userRepository.findAll();
    }
```

note:
    web based admin
