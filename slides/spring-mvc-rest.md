##  Spring MVC REST

- best rest framework in java
- high performance
- MockMVC for testing

```java
    @RequestMapping(value = "/users",
        method = RequestMethod.GET,
        produces = MediaType.APPLICATION_JSON_VALUE)
    public List<User> getAll() {
        log.debug("REST request to get all Users");
        return userRepository.findAll();
    }
```

note:
    Put your speaker notes here.
    You can see them pressing 's'.
