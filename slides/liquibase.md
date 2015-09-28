##  Liquibase

### database refactoring

- Change POJO class
- Run maven plugin
```mvn liquibase:diff```
- ChangeSet will be generated
```xml
<changeSet id="20150816034118" author="jhipster">
    <createTable tableName="LISTING">
        <column name="name2" type="varchar(255)"/>
    </createTable>
</changeSet>
```

note:
- database schema changelog
- change POJO -> generate change set
- handles updating a database schema
- works great with Spring & JPA
