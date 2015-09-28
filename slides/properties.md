##  Properties

- application-dev.yml

```yml
spring:
    profiles:
        active: dev
    datasource:
        dataSourceClassName: com.mysql.jdbc.jdbc2.optional.MysqlDataSource
        url: jdbc:mysql://localhost:3306/IsceUpdatingPlatform?useUnicode=true&characterEncoding=utf8
        databaseName: isceupdatingplatform
        serverName: localhost
        username: root
        password: pwd123
        cachePrepStmts: true
        prepStmtCacheSize: 250
        prepStmtCacheSqlLimit: 2048
        useServerPrepStmts: true
```

note:
    Put your speaker notes here.
    You can see them pressing 's'.
