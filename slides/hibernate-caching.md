##  Hibernate Caching

- King for performance
- Ehcache is the most widely used solution

```java
@Entity
@Cache(usage = CacheConcurrencyStrategy.NONSTRICT_READ_WRITE)
public class User implements Serializable {

}
```

note:
- HazelCast, clustering support
